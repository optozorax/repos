+++
title = "Repositories"
weight = 40
description = "Short descriptions of my repositories."

[taxonomies]
tags = ["systematization"]

[extra]
image = "img/GitHub_Logo.png"
button = { text = "Repository of this page", link="https://github.com/optozorax/repos" }

[extra.translation]
from = "ru"
by = "Claude Opus 5.5"
+++

All repositories are sorted by my subjective rating of how good they are. The higher up a repository is, the better I think it is.

# My coding projects

All the projects that involve programming.

|Link|Description|
|-|-|
|[space_objects](https://github.com/optozorax/space_objects)|A library for working with coordinate systems and transformations between them. It abstracts working with coordinate systems so powerfully that I use it in every project of mine that has even a little bit of graphics.|
|[portals_opengl](https://github.com/optozorax/portals_opengl)|Rendering portals with OpenGL; it supports not only recursive portals, but volumetric ones too.|
|[path-tracing](https://github.com/optozorax/path-tracing)|I completely rewrote [this ray tracer](https://github.com/optozorax/ray-tracing) from scratch, improved the architecture, and added the ability to render not only with path tracing (photorealistic graphics) but also with ray tracing (fast, but not as realistic). Used in many of my other projects.|
|[ray-tracing](https://github.com/optozorax/ray-tracing)|A fork of some guy's code from GitHub. I chose his code in particular because it was as simple as it gets, compiled without problems, and gave impressive results. With this code I understood for the first time how ray tracing works, and decided to dig into it even deeper by improving the code and adding a couple of features.|
|[keyboard_layout](https://github.com/optozorax/keyboard_layout)|My keyboard layout plus tools for recording and displaying keypress statistics.|
|[TinyWindowsGraphics](https://github.com/optozorax/TinyWindowsGraphics)|My second wrapper over WinAPI functions. It inherits the ideas of [GraphWinApi](https://github.com/optozorax/GraphWinApi), but with a much more thought-out architecture. It also contains a wrapper over [AGG](https://github.com/tomhughes/agg) for anti-aliased drawing, as well as [EasyBMP](http://easybmp.sourceforge.net/) and [STB](https://github.com/nothings/stb) for saving images to files. It's used in many of my other projects, though not as a library for building applications, but as a graphics library. And I think the part responsible for colors, points and drawing should be moved out into a separate lib.|
|[olymp](https://github.com/optozorax/olymp)|Solutions to competitive programming problems. So far, all the problems in this repository are taken from and checked on [olymp.nstu.ru](http://olymp.nstu.ru) (in Russian).|
|[partially-drawing-image-algorithm](https://github.com/optozorax/partially-drawing-image-algorithm)|An algorithm for drawing an image that hasn't been fully received yet. It defines not only the order in which the pixels are traversed, but also the algorithm for drawing the image itself. I used it for ray tracing, to show in real time what was taking a very long time to render. Running time with respect to the number of pixels: linear. Unfortunately, it depends on [TWG](https://github.com/optozorax/TinyWindowsGraphics), so nobody except me will be able to use it.|
|[GraphWinApi](https://github.com/optozorax/GraphWinApi)|A wrapper over WinAPI functions. One of my first libraries and big programs in C++, so the code is really ugly.|
|[slovo-gonka](https://github.com/optozorax/slovo-gonka)|A program for learning English words. The interface is as simple as it gets: a word in English and four buttons where you have to choose the right answer. Built on [TWG](https://github.com/optozorax/TinyWindowsGraphics). I don't actually learn words with it \*facepalm\*.|
|[slovo_gonki2](https://github.com/optozorax/slovo_gonki2)|A project to write a new app for learning English words, together with [Ldaon](https://github.com/Ldaon). Still in development.|
|[fast_tree_point_in_polygon](https://github.com/optozorax/fast_tree_point_in_polygon)|An attempt to invent an algorithm for checking whether a point lies inside a polygon by decomposing the polygon's space into a tree. The attempt failed, or maybe I just didn't have enough patience.|
|[keyboard](https://github.com/optozorax/keyboard)|An attempt to write code that finds the optimal layout based on the idea of chords. I abandoned the project because of the incredible complexity I had piled up for myself (I wanted to account for layers and duplicated keys at the same time). [Layout development diary](http://klavogonki.ru/u/#/517589/journal/5b6df4cddf4e4d55728b4567) (in Russian).|

# Articles, assorted writing, LaTeX

|Link|Description|
|-|-|
|[newtons_method_article](https://github.com/optozorax/newtons_method_article) (in Russian)|I explain how Newton's method for solving systems of nonlinear equations works. I try to explain it in as much detail and as well as I can. I wanted to write it after I had figured it out myself and couldn't find anything like it on the internet.|
|[Math formulas](https://github.com/optozorax/math-formulas) (in Russian)|I've been collecting every math formula I can since my school days.|
|[Lab report in LaTeX](https://github.com/optozorax/latex_report) (in Russian)|Since I've been writing my reports in LaTeX since my third year, I decided to gather most of the stuff I use in one place, along with a title page template. It's much more convenient than Word for generating tables, plots and math formulas. But unfortunately, the learning curve is very steep, and in the six months this repository has existed, none of my classmates has ever used it.|
|[This site](https://github.com/optozorax/optozorax.github.io)|No comment.|
|[sun-eclipses](https://github.com/optozorax/sun-eclipses) (in Russian)|Once, with the help of some program, I collected all the solar eclipses of the 21st century in one place, so that search engines would index it and I would become popular. The attempt failed, but at least I know when the next solar eclipse in my city will be.|


# University lab assignments

I posted them so I could tell my classmates `look on GitHub to see how I did it`, and also to have lots of green squares in my daily activity, as if to say I'm not just goofing off. There are also some genuinely good repositories among them.

|Link, Name|Course description|
|-|-|
|[cgi_labs](https://github.com/optozorax/cgi_labs), [Computer graphics](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%8F_%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B0) (in Russian)|We write simple applications using OpenGL.|
|[numerical_methods](https://github.com/optozorax/numerical_methods), [Numerical methods](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A7%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B) (in Russian)|We write methods for solving systems of linear equations. But the systems aren't given in a dense format, but in a sparse format with lots of zeros. And they have to be solved in that same format. This is used in the finite element method (FEM), where each element has only a few neighbors, and when RAM is limited to gigabytes and time to weeks (if you build the matrix with all its zeros, you won't find enough RAM to store it all or enough time to wait for it).|
|[labs_emf](https://github.com/optozorax/labs_emf), [Equations of mathematical physics, part 2](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A3%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9_%D1%84%D0%B8%D0%B7%D0%B8%D0%BA%D0%B8_(%D0%A7%D0%B0%D1%81%D1%82%D1%8C_2)) (in Russian)|We implement methods for solving the differential equations from the first part of this course, using methods similar to [FEM](https://en.wikipedia.org/wiki/Finite_element_method). The bad thing about this course is that the course manual is terribly written, nothing makes sense, the research tasks are pointless, and we don't simulate any physical processes, only abstract spherical cows in a vacuum. On the plus side, my term project came out almost divine.|
|[optimization_methods](https://github.com/optozorax/optimization_methods), [Optimization methods](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%9C%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D0%BE%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8) (in Russian)|We write and study methods for finding the minima and maxima of multivariate and one-dimensional functions.|
|[matstat_rgz](https://github.com/optozorax/matstat_rgz), term assignment in [mathematical statistics](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A2%D0%B5%D0%BE%D1%80%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D0%BE%D1%8F%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9_%D0%B8_%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0_(%D0%A7%D0%B0%D1%81%D1%82%D1%8C_2)) (in Russian)|The LaTeX is just really pretty, that's all.|
|[labs_machine_learning](https://github.com/optozorax/labs_machine_learning), [Project work, part 2](https://project-study.nstu.ru/project.php?id=373) (in Russian)|We study computer vision with convolutional neural networks, using cat and dog recognition as an example.|
|[numerical_simulation_of_ODE](https://github.com/optozorax/numerical_simulation_of_ODE)|We write solvers for ordinary differential equations and apply them to some physics problems. Since the course was only introduced in our year, I tried to write my own course manual for it.|
|[labs_translation_methods](https://github.com/optozorax/labs_translation_methods), [Compiler construction](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%AF%D0%B7%D1%8B%D0%BA%D0%B8_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%B8_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%82%D1%80%D0%B0%D0%BD%D1%81%D0%BB%D1%8F%D1%86%D0%B8%D0%B8) (in Russian)|We write our own compiler for a very small subset of C. The course is meant to teach how compilers work and to study programming concepts such as finite state machines and grammars. Most of the code wasn't written by me.|
|[cryptography](https://github.com/optozorax/cryptography), Cryptography|Simple labs for mastering basic cryptographic concepts, such as letter frequency, hashes, the Diffie–Hellman protocol, public and private keys, symmetric and asymmetric encryption. The coolest thing in this repository is a program that automatically decrypts text encrypted by permuting the letters of the alphabet (a simple substitution cipher). For this I use a genetic algorithm and clever metrics based on bigram and trigram frequencies. See folder `1` for it.|
|[assembler](https://github.com/optozorax/assembler)|Learning MASM assembly and using it from C++.|
|[resources_control_labs](https://github.com/optozorax/resources_control_labs), [Resource management in computer systems](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D1%80%D0%B5%D1%81%D1%83%D1%80%D1%81%D0%B0%D0%BC%D0%B8_%D0%B2_%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D1%85_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%D1%85) (in Russian)|We write programs that use Linux features such as `fork`, `pipe`, `execl`, `openp`. Thanks to this course I realized that either I don't understand Linux, or it has a terrible architecture!|
|[prolog](https://github.com/optozorax/prolog), [Prolog](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B2_%D0%B8%D1%81%D0%BA%D1%83%D1%81%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9_%D0%B8%D0%BD%D1%82%D0%B5%D0%BB%D0%BB%D0%B5%D0%BA%D1%82_%D0%B8_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5) (in Russian)|We write simple programs in this language.|
|[machine_learning](https://github.com/optozorax/machine_learning)|Some kind of decision trees, I can't make heads or tails of it.|

# Forks of other people's repositories

|Link|Description|
|-|-|
|[differential-evolution](https://github.com/optozorax/differential-evolution)|I slightly improved the original [differential evolution](https://en.wikipedia.org/wiki/Differential_evolution) code, turning it into a single file and removing the dependency on Boost.|
|[my-keyboard-layout-editor](https://github.com/optozorax/my-keyboard-layout-editor)|My version of [this site](http://www.keyboard-layout-editor.com/) with a nice style and fixed saving of the layout to JSON.|
|[keyboard-layout-editor](https://github.com/optozorax/keyboard-layout-editor)|My version of [this site](http://www.keyboard-layout-editor.com/) with a fix for saving the layout to JSON, made to show in an [issue](https://github.com/ijprest/keyboard-layout-editor/issues/223#issuecomment-427575038) how this problem can be solved simply.|
