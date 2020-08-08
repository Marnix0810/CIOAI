# CIO AI

A digital assistant like the movies have. Well, if I manage to create it.

## Contents
- [**How to start**](#how-to-start)
- [License](#License)
- [Log](#Log)
- [Dependency repositories](#Dependency-repositories)

## How to start?
_The project did not yet come at a phase where it is runnable. The steps that follow will become more clear and will get addition as there's a lot of changes coming. But by running it you can debug everything that does exist today and will get finished tommorow._ :wink:

```shell
# This code is to be runned in a MacOS/Linux terminal, Powershell.
#
# Dependencies before running:
# - Rust (rustup, rustc and gargo)
# - Git
# - A stable internet conection
#
# Step one: The creation of the project space.
mkdir ./CIO
cd ./CIO/
mkdir ./Dependency-repositories
# Step two: The cloning of the project.
# The project itself...
git clone https://github.com/Marnix0810/CIOAI.git
git clone https://github.com/Marnix0810/cio-finit.git
# ...and the dependency-repositories that actually have value!
cd ./Dependency-repositories
git clone https://github.com/Marnix0810/cio-datacore-init.git

```




## License

The project is licensed under a edited version of my own license ([The 0810 simple and permissive license](https://github.com/Marnix0810/0810-SPL) (rev. [1.2](https://github.com/Marnix0810/0810-SPL/blob/master/latest-1.2/0810-SPL1.2.md))), but it's a private project, so I don't think anyone will ever open it, but if you read this, I probably did ;).

### [License.md](./License.md):

> # The 0810 simple and permissive license (rev. 1.2)
>
> This software, or at least the code licensed with this license is licensed by Marnix Bloeiman, and can be called 'their' code1
>
>
>
> This license gives permission to share, edit, copy, merge, republish or publish the code licensed with this license, however when publishing in any way, you must use the same license (the exact same license, not just **'The 0810 simple and permissive license'** but this exact variant, with the name of the original licenser above) also you may not anywhere in it's code, the code that you added to it or merged with it imply or pretend it's your code or software, you can say *a piece of the software was made by you*, but you may not take the full credit. Also you may not sell the code applying without sufficient changes first.
>
>
>
> [**1**]    (When talking about it's code, we also mean the entire software itself.)
>
>
>
> ## TL;DR:
>
> ### You may:
>
> - Share
> - Edit
> - Copy
> - Merge
> - Publish
> - Republish
> - Sell
>
> *This code or software.*
>
> ### Under the following circumstances:
>
> - Keep the exact same license (file)
> - Don't imply or pretend you made this software (also a '[You may not](#But-you-may-not-)')
>
> ### But you may not:
>
> - Sell the code or software without sufficient changes.
> - Imply or pretend you made the software or code in it.
>
> *Unless specifically given permission by the licenser, **this permission has to be specifically added to this file***.
>
> ## List of exceptions added by licenser:
>
> - The data this project has learned should be classified as private data in property of Marnix Bloeiman and has although been collected by the proect to make its progress, not been published and does not fall under this license, instead as being private data, it should be removed in any distributed copy of this project.
> - This is a project meant for private usage and its code may give acces to private data. The parts of code where this data is available need to be edited in order to keep data private.
>
> ## About the license itself
>
> This license, **'The 0810 simple and permissive license'** has been created by [Marnix B](https://github.com/Marnix0810), this license can be used freely for your own project, but without any warranty or backup from Marnix B.

## Log

like a real scientist I'll log most of the things I do for future reference.

See [PROJECT-LOG.MD](./PROJECT-LOG.MD).

## Dependency repositories
### [cio-datacore-init](https://github.com/Marnix0810/cio-datacore-init)
> `cio-datacore-init` initializes  the 'DATACORE' for the CIO AI project to run.
