```rust
impl YummyOreo {
    pub fn new() -> Self {
        YummyOreo {
            interests: vec!["Coding", "Ultimate Frisbee", "Embedded", "Microbiology", "Dnd", "Panting minis"],
            code: vec![Lang::Rust, Lang::Python, Lang::Java, Lang::Typescript],
            tools: vec![Tool::Neovim, Tool::Atuin, Tool::Nushell, Tool::Lazygit],

            site: "oreo.is-a.dev",
        }
    }

    pub fn current_projects(&self) -> Vec<Project> {
        vec![Project::Onyx]
    }

    pub fn latest_blogs() -> Vec<Blog> {
        vec![

        ]
    }
}
```
