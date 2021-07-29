# phart project

the phart project brings a more cohesive way to run, manage, test, lint and develop php applications.

it's heavily inspired from `deno` and `cargo` commands that provides basic dev tooling under the same executable.

features list (mostly integration stuff):
- [ ] php version management: inspired from `rustup`, you can install **any** php version independently of your os (even on Windows);
- [ ] project management: create new projects, on-the-fly, with various pre-defined steps;
- [ ] composer dependency management: install, update, remove 3rd party libraries;
- [ ] phpunit testing: install, run and coverage your code;
- [ ] php-cs-fixer: lint and format your code accordingly;
- [ ] static analysis: use psalm to ensure your code is safe and sound;

main goals of this project:
- to provide **basic, good** php development setup;
- to help you do stuff without headache of installing and configuring any tools;
- to provide a quick and simple way to create new php projects, even if you don't have php installed.

non-goals of this project:
- to replace composer, phpunit, php-cs-fixer, psalm or any other tools this project is using;
- to replace any of your tools. if you want phpstan instead of psalm, that's fine, you can wire it up;

## still wip
it's not ready to use for production, yet. i'm throwing some lines of code now and then.

## contributing
just setup the rust tooling and... that's how you get ants.
