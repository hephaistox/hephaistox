# hephaistox

## Repositories

Repositories are structured with:

* `automaton`: libraries that can be reused between projects,
  *  they are public
  *  they're deployed to clojars
* `cust-app`: final applications that can be made private,
  * they are generally private as they contain customer knowledge,  
* `monorepo`: gathers many projects in one
  * they are meant for the need of a specific developper or team
  * should contain all projects that may have some impact of the modified projects, otherwise later on updates may be painful,
