<h2 align="center"><img src="https://s8.gifyu.com/images/979447220829032478.gif" height="25px"></h2>

```rust
trait Summary {
    fn new(name: &'static str, attributes: Attributes) -> Self;
}

#[derive(Debug)]
struct Environment {
    editor           : &'static str,
    window_manager   : &'static str',
    operating_system : &'static str,
}

#[derive(Debug)]
struct Programming {
    expert       : [&'static str; 3],
    intermediate : [&'static str; 6],
    learning     : [&'static str; 3],
}

#[derive(Debug)]
struct Attributes {
    interest           : [&'static str; 5],
    natural_langauge   : [&'static str; 2],
    environment        : Environment,
    technical_language : Programming,
}

struct Person {
    name       : &'static str,
    attributes : Attributes,
}

impl Summary for Person {
    fn new(name: &'static str, attributes: Attributes) -> Person {
        Person {
            name,
            attributes,
        }
    }
}

fn main() {

    let environment = Environment {
        editor           : "vim",
        window_manager   : "dwm",
        operating_system : "linux",
    };

    let programming = Programming {
        expert       : [ "python", "c#", "bash" ],
        intermediate : [ "c", "c++", "vimscript", "lua", "haskell", "java" ],
        learning     : [ "rust", "wasm", "typescript" ],
    };

    let my_attributes = Attributes {

        interest           : [
            "Distributed-Systems",
            "Software-Architecture",
            "Web3-stack",
            "Algorithms",
            "Backend-Engineering"
        ],
        natural_langauge   : [ "English", "Indigenous" ],
        environment,
        technical_language : programming,
    };

    let my_name = "zipyx";
    let person: Person = Person::new(
        my_name,
        my_attributes,
    );

}
```

<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cs,bash,c,cpp,vim,lua,haskell,rust,wasm,typescript,androidstudio,aws,docker,dotnet,dynamodb,git,github,gitlab,linux,md,mysql,neovim,nodejs,postgres,postman,raspberrypi,sqlite,visualstudio,vscode" />
  </a>
</p>

<p href="https://discord.gg/onlp" align="center">
    <img alt="" src="https://github-readme-stats.vercel.app/api?username=zipyx&theme=tokyonight&show_icons=true">
</p>
