Hello!

This is a simple Rust webassembly project that use Seed framework along with Tailwind integration.

I wrote a blog post explaining about this project here: https://blog.fakhrusy.com/rust-wasm-seed-trunk-tailwind

To run the project, we need to install some CLI dependencies:

```sh
cargo install trunk
cargo install wasm-bindgen-cli
```

After that, we need to install npm dependencies:

```sh
npm install
```

Then, run two separate script on a different terminal tab:

```sh
npm run css:dev
npm run dev
```

Thank you for having me