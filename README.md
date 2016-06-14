# Running Rust/Cargo Project on Xcode on Mac OS X
This is an Xcode 'external build system' configured to build and run a Rust/cargo project for demo purpose.

# How to do this
- Initialize and setup git ( or your favourite VCS ) in your project directory
- Create a new cargo project ( e.g. cargo new project_name --bin )
- Xcode > New > Project > Other > External Build System
- Configure 'External Build Tool Configuration' for 'cargo build' ( Check this project's configuration for reference )
- Edit Current Scheme > Build > Post Build Action and configure it for 'cargo run' ( Check this project's configuration for reference  )
- Any Other settings that you would like to configure ..
- Done !

This project was created using Xcode 7.3.1 on Mac OS 10.11.5

# But Why ?
Because you can. ( and because some people love Xcode ) 

# Contact
I doubt whether anyone will need support for this but here is my mail anyway : 
sidbhatt11 [at] yahoo [dot] in

Any feedback is welcome !

