# Create-Variable
fn main() {     let x = 5;     println!("Значення x: {}", x);     // x = 10; // Це викличе помилку компіляції } fn main() {     let mut y = 5;     println!("Значення y: {}", y);     y = 10; // Тепер це дозволено     println!("Новое значення y: {}", y); } fn main() {     let z: i32 = 10; // i32 - цілочисельний тип     
