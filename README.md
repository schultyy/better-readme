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


## Misc

### Active Language

Use active language to describe your project and steps users need to take. For instance:

```
Visit [link] to find the Getting Started Guide.
```

And avoid:

```
A getting started guide can be found here.
```

### How to describe your project

Depending on the type of project, you might want to describe it to your audience differently. Let's consider two examples.

#### Security / Safety with [Devise](https://github.com/heartcombo/devise)

Devise is a Ruby library to help developers implement authentication in their [Rails](https://rubyonrails.org/) application.

A user that works on authentication needs to fulfill security requirements. Unmet security requirements are often stress-inducing, therefore it is our job to help the user to reduce stress as much as possible.

How can we avoid triggering stress?

We emphasize that the library is well-tested and uses established protocols and mechanisms to implement authentication.
We want to make sure the user knows that they are using a safe library to solve their problems, without causing any surprises.

#### New approaches with [Hotwire](https://hotwire.dev)

Hotwire is an alternative approach to building modern web applications without using much JavaScript by sending HTML instead of JSON over the wire.

Compared to other techniques and libraries, it's a new approach. People looking at it might not have any idea how it could be useful.
Therefore, Hotwire requires different language to explain it to users compared to Devise.

Instead of being cautious and emphasizing battle-tested approaches, we want to showcase all the new opportunities this approach offers.

