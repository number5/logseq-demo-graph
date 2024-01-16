tags:: #[[SRE Lightning Talks]] #Rust #tools
date:: [[2022-08-24 Wednesday]]

-
- My Rusty Toolbelt
- [ripgrep](https://github.com/BurntSushi/ripgrep)
	- Ripgrep is a grep killer
	- [Tag](https://github.com/aykamko/tag) is a little helper to launch your rg match in your editor (you need to use `go install ` if you're using M1 Mac like me)
- [exa](https://github.com/ogham/exa)
	- exa is the new `ls`
- [Starship](https://starship.rs/)
	- The minimal, blazing-fast, and infinitely customizable prompt for any shell!
- [Dust](https://github.com/bootandy/dust)
	- Dust is the new `du`
- [Difftastic](https://difftastic.wilfred.me.uk/)
	- Difftastic is a structural diff tool that understands syntax. It supports [over 20 programming languages](https://difftastic.wilfred.me.uk/languages_supported.html) and when it works, it's *fantastic*.
- [sheldon](https://sheldon.cli.rs/)
	- shell plugins manager not written in shell
	- Sheldon is a fast, configurable, command-line tool to manage your shell plugins.
- [git-trim](https://github.com/foriequal0/git-trim)
	- A more powerful / feature-complete "hub sync"
- [xh](https://github.com/ducaale/xh)
	- [httpie](https://httpie.io/cli) in Rust
	- httpie is the new curl
	- Curl itself are going to have bunch of Rusty parts as well https://daniel.haxx.se/blog/2022/02/01/curl-with-rust/
- [fd](https://github.com/sharkdp/fd)
	- fd is the new `find`
	- `fd`  is a program to find entries in your filesystem. It is a simple, fast and user-friendly alternative to [ `find` ](https://www.gnu.org/software/findutils/).
- [bat](https://github.com/sharkdp/bat)
	- Bat is the new cat
	- A *cat(1)* clone with syntax highlighting and Git integration.
- Where are they?
	- `~/.cargo/bin`
	- `brew uses --include-build --installed rust`
		- ```
		  λ brew uses --include-build --installed rust                         14:21:20
		  awscli                     git-delta                  ripgrep
		  bat                        gitui                      selene
		  broot                      librsvg                    sheldon
		  certbot                    loc                        starship
		  cloudformation-guard       lsd                        tokei
		  dog                        mdcat                      tree-sitter
		  dust                       mitmproxy                  websocat
		  exa                        newsboat                   xh
		  fd                         nushell                    ykman
		  fselect                    rav1e                      zoxide
		  ```
		-