Exploring rust and having fun with the fundamentals.


## Vectors / Lists

- **Vec<> (Vectors / Lists)**: `Vec<T>` is a dynamically sized collection, meaning it can grow or shrink at runtime. Unlike arrays, which are fixed in size, vectors are more flexible. They are often used when the size of the collection is not known in advance.

- **Arrays**: Arrays in Rust are fixed-size collections. Once the array size is defined, it cannot be changed. All elements in an array must be of the same type, and the size must be known at compile time.

---

## Bindings (Immutable) / Mutability

- **Immutable Bindings**: In Rust, variables are immutable by default. This means that once a value is assigned to a variable, it cannot be changed. This immutability helps prevent bugs and ensures the safety of data throughout the program.

- **Mutable Bindings (`mut`)**: To modify a value after it’s been assigned, the `mut` keyword is used. This makes a variable mutable, allowing its value to be updated during the program’s execution.

---

## Crates

- **Crates**: Crates are packages of Rust code that can be reused in your project. The Rust package manager, **Cargo**, helps manage these crates. Crates can either be external libraries or local modules within your project.

- **Cargo**: Cargo is the tool used to build, test, and manage Rust projects. It also handles downloading and compiling dependencies from the online repository of crates, called **crates.io**.

---

## Mapping and Importing

- **`use` Keyword**: The `use` keyword in Rust brings items like modules, functions, or types into scope, making them available for use in your program. This helps keep the code clean and avoids long paths for accessing types and functions.

- **Path Separator (`::`)**: The `::` syntax is used to access functions, structs, or other items within a module or crate. It is used to specify the path to an item when importing or calling it.

---

## Methods

- **Methods**: In Rust, methods are functions that are associated with a specific type (typically a `struct` or `enum`). These functions can be called on instances of the type and are usually defined inside an `impl` block.

---

## Associated Functions

- **Associated Functions**: These are functions that belong to a type but do not require an instance of that type to be called. They are defined using the `impl` keyword and are typically used for creating constructors or utility functions related to the type.

---

## Implicit Return

- **Implicit Return**: In Rust, if a function's last expression does not have a semicolon, it is automatically returned as the result of the function. This means the return value is inferred, and you don't need to explicitly use the `return` keyword unless you prefer to do so.

---

## Attribute Annotations

- **Attribute Annotations**: These are used to provide metadata for the compiler, like automatically implementing traits or configuring the build process. Common examples include `#[derive(Debug)]`, which automatically generates the code for the `Debug` trait, allowing you to print the struct in a readable format.

---

## Struct

- **Struct**: A `struct` in Rust is a custom data type that allows you to group related data together. It is similar to classes in other object-oriented languages, but Rust focuses on data safety and performance. Structs can have fields, and methods can be associated with them.

---
