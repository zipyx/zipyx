<h2 align="center">Student <img src="https://s8.gifyu.com/images/979447220829032478.gif" height="25px"> Learner</h2>

```rust
trait Summary {
    fn new(name: String, attributes: Attributes) -> Self;
}

#[derive(Debug)]
struct Programming {
    expert       : [&'static str; 3],
    intermediate : [&'static str; 6],
    learning     : [&'static str; 4],
}

#[derive(Debug)]
struct Attributes {
    environment        : String,
    interest           : [&'static str; 5],
    natural_langauge   : [&'static str; 2],
    technical_language : Programming,
}

struct Person {
    name       : String,
    attributes : Attributes,
}

impl Summary for Person {
    fn new(name: String, attributes: Attributes) -> Person {
        Person {
            name,
            attributes,
        }
    }
}

fn main() {

    let programming = Programming {
        expert       : [ "python", "c#", "bash" ],
        intermediate : [ "c", "c++", "vimscript", "lua", "haskell", "java" ],
        learning     : [ "rust", "wasm", "typescript", "javascript" ],
    };

    let attributes = Attributes {

        interest           : [
            "Distributed-Systems",
            "Blockchain",
            "Web3-stack",
            "Algorithms",
            "Backend-Engineering"
        ],
        environment        : String::from("Vim / Neovim"),
        natural_langauge   : [ "English", "Indigenous" ],
        technical_language : programming,
    };

    let person: Person = Person::new(
        String::from("zipyx"),
        attributes,
    );

    println!("Name: {}", person.get_name());
    println!("Attributes: {:?}", person.get_attributes());
}
```

<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,cs,bash,c,cpp,vim,lua,haskell,rust,wasm,typescript,javascript,androidstudio,aws,docker,dotnet,dynamodb,git,github,gitlab,linux,md,mysql,neovim,nodejs,postgres,postman,raspberrypi,sqlite,visualstudio,vscode" />
  </a>
</p>

<p href="https://discord.gg/onlp" align="center">
    <img alt="" src="https://github-readme-stats.vercel.app/api?username=zipyx&theme=tokyonight&show_icons=true">
</p>
