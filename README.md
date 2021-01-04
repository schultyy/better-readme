# better-readme

Your brand-new project is ready for the first users, yet once you start talking about it, nobody cares. Have you experienced this as well in the past?

Then we should talk about `README.md` files. A README file helps to set the tone, explain what your project is all about and get visitors excited to try it out and contribute. Most importantly, GitHub by default shows the contents of your project's `README.md` by default.
Therefore, it's the first interaction your users will have with your project.

## How does a good README file look like?

### Introduction

First of all, let's explain what the project is about. What does it do, for whom is it interesting?

For instance:

> Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

That's step one.

Now, in the next sentence, let's explain who our target user is.

> Deno is a JavaScript Runtime aimed towards developers who are security-conscious and want to work with TypeScript out of the box.

It's important to explain who you want to use your product.

### Installation

Explain in simple steps, how I can install the project or library on my computer. Depending on my operating system, include different instructions, if necessary.

For instance:

> Shell (Mac, Linux):

`curl -fsSL https://deno.land/x/install/install.sh | sh`

> PowerShell (Windows):

`iwr https://deno.land/x/install/install.ps1 -useb | iex`

### Getting Started

How can I use the project with the *least* number of steps possible? Here is space for your "Hello World" equalivant:

`$ deno run https://deno.land/std/examples/welcome.ts`

### Contributing

If I'd like to contribute, what steps do I have to follow to submit any changes?

Explain, how users should use GitHub Issues for this project. 

Also, explain how they can submit code changes to your project. For instance:

1. Fork this project.
2. Check out a new branch: `git checkout -b feature-branch`.
3. Make Changes.
4. Commit Changes `git add . && git commit`. 
5. Open a Pull Request against this project's `main` branch.

In your PR description, please explain why you submitted the PR and all other necessary context.
