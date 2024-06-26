# hello rust


## Sample
1. create a new rust project by `cargo new`
```
cargo new hello
cd hello
```

2. init project
```
git add .
git commit -m "init"
```

3. create repository on github

4. push this repository to github
```
git remote add origin git@github.com:zyyang90/hello.git
git branch -M main
git push -u origin main
```

5. run with `cargo run`

```
cargo run
```

6. add `Cargo.lock` to .gitignore

7. push first commit 

```
git add .
git commit -m "first commit"
git push origin main
```

## Summary
1. use `cargo new` to create a new Rust project
2. create repository on github, and push codes to github
3. use `cargo run` to run the project: hello
4. Cargo.lock is generate by `cargo`, which should add to .gitignore