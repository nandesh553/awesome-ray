# awesome-ray
Everything to get industrial ray applications running in production

<!--lint ignore double-link-->
# Awesome RAY [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[<img src="https://raw.githubusercontent.com/ray-project/ray/master/doc/source/images/ray_header_logo.png" alt="Ray Logo" align="right" height="100">](https://github.com/ray-project/ray/)

![ray_logo](https://user-images.githubusercontent.com/20907377/175792492-a085fc63-3b5f-4804-8215-e9c45cb284aa.gif)

<!--lint ignore double-link-->
[Ray](https://github.com/ray-project/ray/) makes it effortless to parallelize single machine code — go from a single CPU to multi-core, multi-GPU or multi-node with minimal code changes.
<!--lint enable double-link-->

This is a curated list of awesome RAY libraries, projects, and other resources. Contributions are welcome!

# Starting fresh
1. Normalising Values
  - https://github.com/ray-project/ray/issues/9399
  - https://discuss.ray.io/t/normalizing-observations/8652 

## Contents

- [Libraries](#libraries)
- [Models and Projects](#models-and-projects)
- [Videos](#videos)
- [Papers](#papers)
- [Tutorials and Blog Posts](#tutorials-and-blog-posts)
- [Community](#community)

<a name="libraries" />

## Libraries

<a name="new-libraries" />

### New Libraries

This section contains libraries that are well-made and useful, but have not necessarily been battle-tested by a large userbase yet.


<a name="models-and-projects" />

## Models and Projects

### Ray + LLM
- [FastChat](https://github.com/lm-sys/FastChat) Vicuna: An Open-Source Chatbot Impressing GPT-4 with 90% ChatGPT Quality
- [LangChain-Ray](https://github.com/ray-project/langchain-ray) Examples on how to use LangChain and Ray
- [Aviary](https://github.com/ray-project/aviary) Ray Aviary - evaluate multiple LLMs easily
- [LLM-distributed-finetune](https://github.com/AdrianBZG/LLM-distributed-finetune) Finetuning Large Language Models Efficiently on a Distributed Cluster, Uses Ray AIR to orchestrate the training on multiple AWS GPU instances.

### Reinforcmenet Learning

- [muzero-general](https://github.com/werner-duvaud/muzero-general) - A commented and documented implementation of MuZero based on the Google DeepMind paper (Schrittwieser et al., Nov 2019) and the associated pseudocode.
- [rllib-torch-maddpg](https://github.com/Rohan138/rllib-torch-maddpg) - PyTorch implementation of MADDPG (Lowe et al.) in RLLib
- [MARLlib](https://github.com/Replicable-MARL/MARLlib) - a comprehensive Multi-Agent Reinforcement Learning algorithm library

### Ray + JAX / TPU

- [Swarm-jax](https://github.com/kingoflolz/swarm-jax) - Swarm training framework using Haiku + JAX + Ray for layer parallel transformer language models on unreliable, heterogeneous nodes
- [Alpa](https://github.com/alpa-projects/alpa) - Auto parallelization for large-scale neural networks using Jax, XLA, and Ray


### Ray + Database

- [Balsa](https://github.com/balsa-project/balsa#cluster-mode) Balsa is a learned SQL query optimizer. It tailor optimizes your SQL queries to find the best execution plans for your hardware and engine.
- [RaySQL](https://github.com/andygrove/ray-sql) Distributed SQL Query Engine in Python using Ray
- [Quokka](https://github.com/marsupialtail/quokka) Open source SQL engine in Python 

### Ray + X (integration)

- [prefect-ray](https://github.com/PrefectHQ/prefect-ray) Prefect integrations with Ray
- [xgboost_ray](https://github.com/ray-project/xgboost_ray) Distributed XGBoost on Ray
- [Ray-DeepSpeed-Inference](https://github.com/tchordia/ray-serve-deepspeed) Run deepspeed on ray serve

### Ray-Project
- [SkyPilot](https://github.com/skypilot-org/skypilot) a framework for easily running machine learning workloads on any cloud through a unified interface
- [Exoshuffle-CloudSort](https://github.com/exoshuffle/cloudsort) the winning entry of the [2022 CloudSort Benchmark](http://sortbenchmark.org/) in the Indy category.

### distributed computing
- [Fugue](https://github.com/fugue-project/fugue) a unified interface for distributed computing that lets users execute Python, pandas, and SQL code on Ray without rewrites.
- [Daft](https://github.com/Eventual-Inc/Daft) is a fast, Pythonic and scalable open-source dataframe library built for Python and Machine Learning workloads.
- [Flower](https://github.com/adap/flower)(flwr) is a framework for building federated learning systems. Uses Ray for scaling out experiments from desktop, single GPU rack, or multi-node GPU cluster.
- [Modin](https://github.com/modin-project/modin): Scale your pandas workflows by changing one line of code. Uses Ray for transparently scaling out to multiple nodes.
- [Volcano](https://github.com/volcano-sh/volcano) is a batch system built on Kubernetes. It provides a suite of mechanisms that are commonly required by many classes of batch & elastic workloads.

### Ray AIR
- [Ray on Azure ML](https://github.com/microsoft/ray-on-aml) Turning AML compute into Ray cluster

### Misc
- [AutoGluon](https://github.com/awslabs/autogluon) AutoML for Image, Text, and Tabular Data
- [Aws-samples](https://github.com/aws-samples/aws-samples-for-ray) Ray on Amazon SageMaker/EC2/EKS/EMR
- [KubeRay](https://github.com/ray-project/kuberay) A toolkit to run Ray applications on Kubernetes
- [ray-educational-materials](https://github.com/ray-project/ray-educational-materials) This is suite of the hands-on training materials that shows how to scale CV, NLP, time-series forecasting workloads with Ray.
- [Metaflow-Ray](https://github.com/outerbounds/metaflow-ray) An extension for Metaflow that enables seamless integration with Ray 

<a name="videos" />

## Videos

<a name="papers" />

### rllib 
- [Deep reinforcement learning at Riot Games by Ben Kasper](https://youtu.be/r6ErUh5sjXQ) - reinforcement learning for game development in production



## Papers

This section contains papers focused on Ray (e.g. RAY-based library whitepapers, research on RAY, etc). Papers implemented in RAY are listed in the [Models/Projects](#projects) section.

<!--lint ignore awesome-list-item-->

<!--lint enable awesome-list-item-->

<a name="tutorials-and-blog-posts" />

## Tutorials and Blog Posts


- [Programming in Ray: Tips for first-time users](https://rise.cs.berkeley.edu/blog/ray-tips-for-first-time-users)
- [Reddit post](https://news.ycombinator.com/item?id=27730807) 
- [Load PyTorch Models 340 Times Faster with Ray](https://medium.com/ibm-data-ai/how-to-load-pytorch-models-340-times-faster-with-ray-8be751a6944c)

## books 

- [Learning Ray](https://github.com/maxpumperla/learning_ray) Learning Ray - Flexible Distributed Python for Machine Learning

## course

- [RL course](https://github.com/anyscale/rl-course) Applied Reinforcement Learning with RLlib
- [MLops course](https://github.com/anyscale/mlops-course) MLops course

## cheatsheet

- [Ray design doc](https://docs.google.com/document/d/167rnnDFIVRhHhK4mznEIemOtj63IOhtIPvSYaPgI4Fg/edit#heading=h.5jeo2fupy3yv)

<a name="community" />

## Community

- [RAY Discussions](https://discuss.ray.io/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ray)
- [Slack](https://forms.gle/9TSdDYUgxYs8SA9e8)
- [GitHub Issues](https://github.com/ray-project/ray/issues)
- [Meetup Group](https://www.meetup.com/Bay-Area-Ray-Meetup/)
- [Twitter](https://twitter.com/raydistributed)

# Awesome raylib

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome stuff for [raylib](https://raylib.com), Simple and easy-to-use library to enjoy videogames programming.

## List

- [Libraries and Frameworks](#libraries-and-frameworks)
- [Softwares](#softwares)
- [Bindings](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)
- [Deprecated/Removed/Unknown bindings](#deprecatedremovedunknown-bindings)
- [Libraries bindings/ports](#libraries-bindingsports)
- [Platforms supported by raylib](https://github.com/raysan5/raylib#building-raylib-on-multiple-platforms)
- [Tutorials](#tutorials)
- [Examples by community](#examples-by-community)
- [Templates](#templates)
- [Articles](#articles)
- [What raylib uses?](#what-raylib-uses)
- [Resources and Links](#resources-and-links)

### Libraries and Frameworks

- [raysan5/raylib](https://github.com/raysan5/raylib), Simple and easy-to-use library to enjoy videogames programming.
- [SasLuca/rayfork](https://github.com/SasLuca/rayfork), Single header and source, cross-platform, allocator-aware, C99 game libraries.
- [Rabios/rayport](https://github.com/Rabios/rayport), Awesome C99, Header-Only, rayfork wrapper for raylib!
- [Rabios/rayutils](https://github.com/Rabios/rayutils), Single-Header library that extends raylib with some awesome functionality!
- [raysan5/raygui](https://github.com/raysan5/raygui), Simple and easy-to-use immediate-mode gui library.
- [victorfisac/Physac](https://github.com/victorfisac/Physac), 2D physics header-only library for videogames developed in C using raylib library.
- [raysan5/rpng](https://github.com/raysan5/rpng), Simple and easy-to-use library to manage png chunks.
- [raysan5/rres](https://github.com/raysan5/rres), Simple and easy-to-use file-format to package resources.
- [raysan5/raudio](https://github.com/raysan5/raudio), Simple and easy-to-use audio library based on miniaudio.
- [firststef/ECSlib](https://github.com/firststef/ECSlib), Library with ECS classes in C++ using raylib.
- [osom8979/tbag](https://github.com/osom8979/tbag), Third party extension utility project.
- [oswjk/imgui-impl-raylib](https://github.com/oswjk/imgui-impl-raylib), Raylib backend for Dear ImGui.
- [haydenhigg/Libre](https://github.com/haydenhigg/Libre), Crystal graphics library that is built on Raylib.
- [nezvers/TileMap](https://github.com/nezvers/TileMap), TileMap system for raylib.
- [nuklear_raylib](https://github.com/RobLoach/nuklear_raylib), Nuklear immediate mode GUI for raylib.
- [zworld-apps/zgui](https://github.com/zworld-apps/zgui), GUI system based on Constraints for raylib, Written in Go.
- [Slixe/visual-go](https://github.com/Slixe/visual-go), Go Framework to create simple application using raylib & Flex.
- [basp1/rlyeh](https://github.com/basp1/rlyeh), Simple and easy-to-use GUI API library for raylib-go, Written in Go.
- [smthnspcl/raycons](https://github.com/smthnspcl/raycons), Icons drawn by raylib, Written in C++.
- [smthnspcl/raygauge](https://github.com/smthnspcl/raygauge), Simple gauges to display values with raylib, Written in C++.
- [dbriemann/libpartikel](https://github.com/dbriemann/libpartikel), Simple particle system library made with and for raylib. Works as header only library.
- [WEREMSOFT/spine-raylib-runtimes](https://github.com/WEREMSOFT/spine-raylib-runtimes), raylib implementation of the C spine runtimes.
- [WEREMSOFT/stl-loader-for-raylib](https://github.com/WEREMSOFT/stl-loader-for-raylib), STL loader for raylib, Allows to load 3dPrinter file types into raylib. 
- [tcfunk/raylib-nuklear](https://github.com/tcfunk/raylib-nuklear), Implementation of Nuklear for the raylib game engine.
- [TheLumaio/Raylib-GBuffers](https://github.com/TheLumaio/Raylib-GBuffers), gbuffer implementation for raylib.
- [tofuengine/tofu](https://github.com/tofuengine/tofu), Lightweight 2D framework with a lo-fi vibe, for fast game prototyping. Uses OpenGL through GLFW3. Scripted in Lua.
- [Ferrohound/RaylibEX](https://github.com/Ferrohound/RaylibEX), raylib Extra incorporates more basic functionality to raylib while keeping the hands-on aspect!
- [JusticeShultz/MathX](https://github.com/JusticeShultz/MathX), Detailed custom math library programmed in C++ by Justice Shultz that includes demos that uses raylib.
- [LilySweetCat/RaylibCs-UI](https://github.com/LilySweetCat/RaylibCs-UI), Just a simple UI using raylib (Can be used as library), Written in C#.
- [QuantScientist/TorchRayLib](https://github.com/QuantScientist/TorchRayLib), CMake based integration of the RayLib library with the Libtorch C++ Deep Learning Library.
- [c-krit/lowel](https://github.com/c-krit/lowel), 2D map loading / saving system for raylib projects.
- [nbdy/ruicf](https://github.com/nbdy/ruicf), C++ raylib ui controls framework.
- [JeffM2501/RLGameGui](https://github.com/JeffM2501/RLGameGui), Resolution independent gui for raylib, Written in C++!
- [I3uckwheat/CHUCK](https://github.com/I3uckwheat/CHUCK), Allows tiled maps to be used with raylib with little trouble.
- [jackcarey/raylib-extensions](https://github.com/jackcarey/raylib-extensions), Modifications and additions to [raysan5/raylib](https://github.com/raysan5/raylib) and [raysan5/raygui](https://github.com/raysan5/raygui).
- [coolcoy12/RayLibUtils](https://github.com/coolcoy12/RayLibUtils), Useful UI and effects for raylib for C++!
- [moonsteal/raylib-barebones](https://github.com/moonsteal/raylib-barebones), Stripped down version of raylib with Meson.
- [Doy-lee/RaylibSIMD](https://github.com/Doy-lee/RaylibSIMD), SIMD Implementation of raylib's API.
- [8bitPandaPlugins/RTAudioGameLib](https://github.com/8bitPandaPlugins/RTAudioGameLib), C++ Game API built on Raylib and RTaudio for latency critical implimentations.
- [TheLumaio/Raylib-GBuffers](https://github.com/TheLumaio/Raylib-GBuffers), GBuffer implementation for raylib.
- [zzador/RayLib-Utilities](https://github.com/zzador/RayLib-Utilities), Some utility & helper functions for raylib and raygui.
- [jozanza/libraygun](https://github.com/jozanza/libraygun), Utils for raylib.
- [JeffM2501/raylibExtras](https://github.com/JeffM2501/raylibExtras), C++ Utilities and common code for use with raylib.
- [Ushio/raylibImGui](https://github.com/Ushio/raylibImGui), C++ Dear ImGui integration for raylib.
- [nicholasimon/displayfx_raylib](https://github.com/nicholasimon/displayfx_raylib), Few effects to use on top of your game screen, scanlines, noise lines and pixel noise, written in Go.
- [JacobLondon/rlgutils](https://github.com/JacobLondon/rlgutils), Golang utilities for raylib.
- [thyliverman/PaperSDL](https://github.com/thyliverman/PaperSDL), Small software library, designed to make using Raylib-CS simpler and more concise, Written in C#.
- [hbiblia/gtk-raylib](https://github.com/hbiblia/gtk-raylib), GTK integration with raylib.
- [QuantScientist/ncnnRay](https://github.com/QuantScientist/ncnnRay), ncnnRay++ is a CMake based integration of raylib and the very popular Tencent ncnn Deep Learning library. ncnn is written in C++ and designed (but not only) for edge computing devices. The project depends on the Vulkan SDK (Vulakn is Khronos' API for Graphics and Compute on GPUs).
- [impzero/gastar](https://github.com/impzero/gastar), Algorithm implemented in Go visualized using raylib.
- [c-krit/ichor](https://github.com/c-krit/ichor), PhysicsFS API wrapper for raylib.
- [thyliverman/Paper](https://github.com/thyliverman/Paper), C++ rewrite of PaperSDL, dedicated to making raylib just a little easier to work with.
- [EMoore13/Animator-For-Raylib-CS](https://github.com/EMoore13/Animator-For-Raylib-CS), Modified version of AliElSaleh's Animator-For-Raylib made to work with the raylib-cs nuget package, Written in C#.
- [AliElSaleh/Animator-For-Raylib](https://github.com/AliElSaleh/Animator-For-Raylib), C/C++ Animator lib.
- [LilySweetCat/RaylibCs-UI](https://github.com/LilySweetCat/RaylibCs-UI), Just a simple UI using raylib, Written in C#.

### Softwares

- [sparkskapil/2D-CAD-Raylib](https://github.com/sparkskapil/2D-CAD-Raylib), 2D CAD viewer for raylib.
- [sorykkk/raygui_calculator](https://github.com/sorykkk/raygui_calculator), Demonstrates simple and functional calculator gui written with raygui based on raylib library.
- [MarcMDE/FunWithEasings](https://github.com/MarcMDE/FunWithEasings), Small and simple Easings visualizing tool developed in C with raylib and C easings.
- [Mudzii/SharedBuff](https://github.com/Mudzii/SharedBuff), Level editor using a shared buffer between an Maya API and rayLib engine.
- [raysan5/rFXGen](https://github.com/raysan5/rfxgen), Simple and easy-to-use fx sounds generator.
- [victorfisac/rPBR](https://github.com/victorfisac/rPBR), 3D model viewer with a physically based rendering (PBR) pipeline written in pure C. The PBR pipeline is written directly using OpenGL and the viewer uses raylib programming library for windows management, inputs and interface drawing.
- [RobLoach/raylib-libretro](https://github.com/RobLoach/raylib-libretro), libretro frontend using raylib.
- [victorfisac/FNode](https://github.com/victorfisac/FNode), Tool based in nodes to build GLSL shaders without any programming knowledge written in C using OpenGL and GLFW.
- [MaximeHouis/RayTracer](https://github.com/MaximeHouis/RayTracer), Ray Tracer in C++ using raylib.
- [parmaja/tyro](https://github.com/parmaja/tyro), Lua and other programming in simple platform to make programming fun.
- [fedqx/GeldaEngine](https://github.com/fedqx/GeldaEngine), C raylib game engine.
- [xdrie/rengfx](https://github.com/xdrie/rengfx), Lightweight, expressive, extensible 2D/3D game engine, Written in D.
- [Rabios/raytaiko](https://github.com/Rabios/raytaiko), Simple Taiko no Tatsujin engine written in Lua using raylib,Via Astie Teddy's LuaJIT binding,Moddable with Lua.
- [Rabios/raylua/tree/master/zerobrane](https://github.com/Rabios/raylua/tree/master/zerobrane), ZeroBrane Studio autocompletion for raylib Lua bindings.
- [nurakmaljalil91/cbit-raylib](https://github.com/nurakmaljalil91/cbit-raylib), C++ Game Engine built on top of raylib.
- [CarterPatterson/PhysicsEngine](https://github.com/CarterPatterson/PhysicsEngine), Simple physics engine built in Raylib for AIE CS 2019, Written in C++!
- [JhnBrunelle/Beam2D-Engine](https://github.com/JhnBrunelle/Beam2D-Engine), C++ ECS game engine based on Raylib and OpenGL.
- [Guevara-chan/Midday-Commander](https://github.com/Guevara-chan/Midday-Commander), •Retrofuturistic file manager•, Written in Nim.
- [hfabre/ttme](https://github.com/hfabre/ttme), Tiny tile map editor, Written in Go.
- [ProfJski/ArtColor](https://github.com/ProfJski/ArtColors), Intuitive color mixing in a subtractive Red-Yellow-Blue color space. A traditional art school color wheel and palette selector for triadic, split-complementary and tetradic color harmonies. RGB-to-RYB conversion with simple formulas. Built with raylib.
- [Demizdor/experimental-raygui-editor](https://github.com/Demizdor/experimental-raygui-editor), Experimental GUI editor for raygui.
- [RobLoach/raylib-meson](https://github.com/RobLoach/raylib-meson), raylib meson build system.
- [rfaile313/Raylib-Buildfiles](https://github.com/rfaile313/Raylib-Buildfiles), Simple Makefile that incorporates Raylib on OS: Windows && Platform: Desktop.
- [redsled84/music-player](https://github.com/redsled84/music-player), Linked list music player using raylib.
- [ArnautDaniel/riley-duper](https://github.com/ArnautDaniel/riley-duper), Application for sorting images based on related "types" of items in the pictures. Riley-Duper will output a hidden file that contains the pictures which are linked together.
- [WEREMSOFT/c99-raylib-vide-player](https://github.com/WEREMSOFT/c99-raylib-vide-player), Videoplayer using raylib. Play unsuported video format by the browser in the broswer.
- [TheLumaio/baslike-editor](https://github.com/TheLumaio/baslike-editor), Editor for baslike written in raylib.
- [pkeckler/PACKER](https://github.com/pkeckler/PACKER), raylib asset packer.
- [ComLarsic/Chip8-raylib](https://github.com/ComLarsic/Chip8-raylib), CHIP8 emulator written in C# using raylib.
- [LesFarrell/Chip8](https://github.com/LesFarrell/Chip8), CHIP8 Emulator / Interpreter using written using C and the Raylib library.
- [ralsina/cobra-py](https://github.com/ralsina/cobra-py), 80s-style Python environment.
- [athreef/Alien-raylib](https://github.com/athreef/Alien-raylib), Alien distribution for raylib video game engine.
- [JusticeShultz/cpp-raylib-tilemap](https://github.com/JusticeShultz/cpp-raylib-tilemap), Source code for a runtime tile map tool in the C++ raylib library.
- [MasterPlan by SolarLune](https://solarlune.itch.io/masterplan), easy-to-use graphical free-flow project management tool and idea board.
- [Cute Exporter by Clay Murray](https://powerc9000.itch.io/cute-asset-pipeline), The best PSD layers to PNG texture atlas exporter.
- [MySprite by TonyButDead](https://tonybutdead.itch.io/mysprite), Free pixel art tool created in the Go programming language with raylib.
- [SeijiEmery's level editor (level editor in a weekend)](https://seijiemery.itch.io/agj-level-editor-in-a-weekend), Quick experiment in building a small game/nice-ish level editor/platformer from scratch with raylib over a weekend.
- [rTexPacker by raylib technologies](https://raylibtech.itch.io/rtexpacker), Simple and easy-to-use textures packer and font atlas generator.
- [rTexViewer by raylib technologies](https://raylibtech.itch.io/rtexviewer), Simple and easy-to-use textures viewer and pixel formats converter.
- [rIconPacker by raylib technologies](https://raylibtech.itch.io/riconpacker), Simple and easy-to-use icons packer.
- [rGuiStyler by raylib technologies](https://raylibtech.itch.io/rguistyler), Simple and easy-to-use raygui styles editor.
- [rGuiLayout by raylib technologies](https://raylibtech.itch.io/rguilayout), Simple and easy-to-use raygui layouts editor.
- [rGuiIcons by raylib technologies](https://raylibtech.itch.io/rguiicons), Simple and easy-to-use raygui icons editor.
- [obaodelana/graphingcalculator](https://github.com/obaodelana/graphingcalculator), Graphing Calculator made with Raylib using C.
- [krsn53/win-3d-maze](https://github.com/krsn53/win-3d-maze), Windows 3D Maze Screensaver in C++ with raylib.
- [MadeleinNyblom/LevelEditor-MayaPlugin](https://github.com/MadeleinNyblom/LevelEditor-MayaPlugin), Level editor that sends information from Maya to a rayLib engine using a circular buffer.
- [kenhyokun/khkFramework-raylib](https://github.com/kenhyokun/khkFramework-raylib), Experimental C/C++ 2D game framework with raylib.
- [HurricaneInteractive/abyss_engine](https://github.com/HurricaneInteractive/abyss_engine), Very simple game engine written in Rust and built on top of raylib-rs.
- [HurricaneInteractive/abyss_editor](https://github.com/HurricaneInteractive/abyss_editor), Editor used for the abyss engine and built using Gatsby and Tauri
- [CorentinLeGuen/RayGame](https://github.com/CorentinLeGuen/RayGame), Map creator with rayLib library written in Python 3.
- [reidevries/CopyCat](https://github.com/reidevries/CopyCat), C++ 17 Game engine based on raylib and EnTT libraries, end goal of creating a tactical RPG.
- [pery77/peryEngine](https://github.com/pery77/peryEngine), C/C++ Retro game engine based on raylib.
- [kuripa/Rayengine](https://github.com/kuripa/Rayengine), C++ Small game engine thats based on raylib.
- [Italian-Coders-Group/Ungine](https://github.com/Italian-Coders-Group/Ungine), Source-like rayLib-based game engine for C++.
- [senior-sigan/chat_from_scratch](https://github.com/senior-sigan/chat_from_scratch), Code from the series of my streams where I work on creating Chat application absolutely from scratch, Written in C++.
- [bayganik/mmGame-Engine-Raylib-ECS](https://github.com/bayganik/mmGame-Engine-Raylib-ECS), C# Game engine using Raylib-CS and Entitas lite as an ECS.
- [xero1/ray-quake](https://github.com/xero1/ray-quake), .NET Core Quake source port built using raylib.
- [practicing01/raylibeditor](https://github.com/practicing01/raylibeditor), Editor made with raylib.
- [pkeckler/PACKER](https://github.com/pkeckler/PACKER), raylib asset packer.
- [parmaja/tyro](https://github.com/parmaja/tyro), Simple graphical environment for kids and newbies, using raylib as small game engine to draw, Written in Pascal.
- [Fakaaa/Raylibculator](https://github.com/Fakaaa/Raylibculator), Calculator made with raylib.
- [Elkantor/raylib_package](https://github.com/Elkantor/raylib_package), BSCXX module for raylib C library.
- [RafaelOliveira/clay](https://github.com/RafaelOliveira/clay), 2D game engine for raylib in C++.
- [sparkskapil/Quill](https://github.com/sparkskapil/Quill), 2D CAD Application using raylib and C++.
- [jmorel33/RayLib-Keyboard-keycode-tester](https://github.com/jmorel33/RayLib-Keyboard-keycode-tester), Keyboard tester made with raylib.
- [kugo12/sponGB](https://github.com/kugo12/sponGB), Gameboy emulator written using Rust and raylib.
- [Veradictus/Kaetram-Raylib](https://github.com/Veradictus/Kaetram-Raylib), C++ Conversion of the Kaetram client to raylib to improve performance and gameplay.
- [trikko/BlobEditor](https://github.com/trikko/BlobEditor), Simple raylib and Dlang project.
- [Andre-LA/nprof](https://github.com/Andre-LA/nprof), Very basic profiler for raylib-nelua.
- [RhettVX/forgelight-raylib](https://github.com/RhettVX/forgelight-raylib), Experimental set of tools for exploring ForgeLight engine game files using raylib and raygui.
- [gergondet/mc_rtc-raylib](https://github.com/gergondet/mc_rtc-raylib), Simple mc_rtc GUI client using raylib.
- [KonPet/Red-Shell](https://github.com/KonPet/Red-Shell), Level Editor for the Mario vs Luigi Python clone made in C++ using raylib.
- [JonSnowbd/XPROEngine](https://github.com/JonSnowbd/XPROEngine), XPRO is a build-inside C game engine that utilizes Raylib/Flecs/Binn to create incredibly fast games with C/Lua.
- [gilzoide/gargula](https://github.com/gilzoide/gargula), Game engine based on nested structs and compile-time tree traversals powered by raylib and D compatible with better C.
- [randevlper/rayoflight](https://github.com/randevlper/rayoflight), 2D Engine implementing Box2D and raylib.
- [notsnail/v2](https://github.com/notsnail/v2), Framework for games built with raylib.
- [erikerlandson/ray-ubi](https://github.com/erikerlandson/ray-ubi), Minimalist Ray distributed computing container image, based on Red Hat UBI.

### Deprecated/Removed/Unknown bindings

- [DevJac/rust_raylib_bindings](https://github.com/DevJac/rust_raylib_bindings), Another rust bindings for raylib.
- [SliverLIVE/Raylib-for-GLBasic](https://github.com/SliverLIVE/Raylib-for-GLBasic), WIP raylib port/bindings for [GLBasic](https://www.glbasic.com).
- [apahl/raylib-swift](https://github.com/apahl/raylib-swift), Helpers for using the raylib C library in Swift.
- [dtcristo/raylib-rust](https://github.com/dtcristo/raylib-rust), Rust bindings for raylib, Removed from bindings list after request from it's dev for being old.
- [mmalecot/rayquaza](https://github.com/mmalecot/rayquaza), Idiomatic Rust wrapper for raylib.

> NOTE: You won't find these bindings in [BINDINGS.md](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)!

### Libraries bindings/ports

- [Dacode45/rayfork-rs](https://github.com/Dacode45/rayfork-rs), Port of rayfork to rust.

### Tutorials

- [Raylib 2.0 Tutorial Series by SkyVaultGames](https://www.youtube.com/playlist?list=PL5gRzHmN4Dg3ubcneVFkHPm0mTGYTUHDn)
- [List of raylib tutorials by HE360](https://www.youtube.com/playlist?list=PLZBVMzyySalVhcWEJcnG-HK8OXQli_tcV)
- [سلسلة تعلم برمجة الألعاب بسي شارب و جافا (Arabic, by Rabia Alhaffar)](https://www.youtube.com/playlist?list=PLZBVMzyySalXG0AdUHJj9rcpd0R7hBczR)
- [How to create a game with 'raylib' in C](https://www.youtube.com/watch?v=kBky9_X8j3Y)
- [How to get started with Raylib 3.0 in C# - Tutorial](https://www.youtube.com/watch?v=SoXD5y24WQw)
- [Let's learn D programming Game Dev!](https://www.youtube.com/playlist?list=PLgM-lc_kSqFQPF0UXgmFZpZalqcrSofe-)
- [Coding a Breakout Arcade clone in C with Raylib](https://www.youtube.com/watch?v=UKecFbu61Oc)
- [Graphics programming challenges by raysan5 (GitHub repository)](https://github.com/raysan5/challenges)
- [How to add hot reload to your raylib project (in C) ?](https://medium.com/@TheElkantor/how-to-add-hot-reload-to-your-raylib-proj-in-c-698caa33eb74)
- [Raylib Game Tutorial : Space Invaders using VSCode](https://monsterbraininc.com/2018/12/raylib-game-tutorial-space-invaders-using-vscode)
- [raylib -- A C++ Game Library That's Perfect For Beginners](https://www.youtube.com/watch?v=xGPF3Gn-yhA)
- [How to build & set up raylib for Visual studio](https://www.youtube.com/watch?v=mfj0JG2LdVM)
- [Create Videos Games in PHP (With RayLib)](https://www.youtube.com/watch?v=q1X_6TYd030)
- [Compiler Raylib sur Windows (French)](https://www.youtube.com/watch?v=XEpmMBM01Zg)
- [Raylib setup on Codeblocks](https://www.youtube.com/watch?v=a2IUxJFr8sg)
- [Tile maps en Raylib con Tileson (Spanish)](https://www.youtube.com/watch?v=Gq9sTaeHtj4)

### Community Examples

- [Lightnet/raylibvscodeexample](https://github.com/Lightnet/raylibvscodeexample), VSCode project sample for raylib.
- [jpike/RayWorld3D](https://github.com/jpike/RayWorld3D), Playing around with raylib's 3D stuff.
- [AliElSaleh/Cosmic-Hell](https://github.com/AliElSaleh/Cosmic-Hell), AIE Holiday Coding Challenge. A Bullet-Hell game that implements flocking in C/C++ using the raylib framework.
- [Skaruts/Game-of-Life-in-Multiple-Languages](https://github.com/Skaruts/Game-of-Life-in-Multiple-Languages), Game of Life implemented in multiple languages and has version for raylib.
- [machinbrol/2d-physics-engine-test](https://github.com/machinbrol/2d-physics-engine-test), 2D-physics-engine test with Go port of raylib.
- [sepisoad/super-janet-typist](https://github.com/sepisoad/super-janet-typist), Short typing game made with Janet Lisp.
- [Ryan1729/nim-raylib-forever-raylib-audio-bug](https://github.com/Ryan1729/nim-raylib-forever-raylib-audio-bug), Example shows audio bug in raylib-forever nim bindings.
- [kebbbnnn/ray-lib-example](https://github.com/kebbbnnn/ray-lib-example), raylib example for MacOS.
- [Dacode45/raylib-physics-example](https://github.com/Dacode45/raylib-physics-example), Rust example of physics specs and raylib all coming together.
- [aaronrcox/EmscriptenHelloRaylib](https://github.com/aaronrcox/EmscriptenHelloRaylib), Emscripten (Web) Starter repo for raylib projects. Web builds are automaticly triggered via Github actions and Deployed to Github Pages.
- [chbdev/raylib-3rdPersonCameraWallDetection](https://github.com/chbdev/raylib-3rdPersonCameraWallDetection), Third person camera wall detection example.
- [gabriellm1/ThreadLab](https://github.com/gabriellm1/ThreadLab), Multi-thread copy and paste program with graphic interface for raylib.
- [jacmoe/permadi-port](https://github.com/jacmoe/permadi-port), Permadi's Raycaster code ported to C++ and raylib.
- [MitchellRB/BinaryTree](https://github.com/MitchellRB/BinaryTree), Visual representation of a binary tree in raylib.
- [xav1t0/Clock](https://github.com/xav1t0/Clock), Clock Made With raylib in C.
- [JRAM0012/rMandelbrotset](https://github.com/JRAM0012/rMandelbrotset), Mandelbrot set visualizer made in raylib.
- [danimartin82/opencv_raylib](https://github.com/danimartin82/opencv_raylib), Tests for mixing OpenCV (4.2.0) with raylib (3.0).
- [Lisoph/RaylibTest](https://github.com/Lisoph/RaylibTest), Examples of messing up with raylib.
- [ianpan870102/raylib-practices](https://github.com/ianpan870102/raylib-practices), Some personal practices with raylib and raylib-cpp in C++.
- [zmontross/cellular_automata](https://github.com/zmontross/cellular_automata), First foray into using raylib as an excuse to practice C programming. No planning, and lots of spaghetti code.
- [Elkantor/simulation](https://github.com/Elkantor/simulation), Flow simulation.
- [albertnadal/Wolf3DClone](https://github.com/albertnadal/Wolf3DClone), Implementation of the "Wolfenstein 3D"(1992) game engine from scratch using vanilla C and raylib.
- [kawa-yoiko/ccleste-raylib](https://github.com/kawa-yoiko/ccleste-raylib), Adaptation of ccleste to raylib with software rendering.
- [EdSwordsmith/LearningRaylib](https://github.com/EdSwordsmith/LearningRaylib), Small projects made with raylib.
- [nikki93/raylib-bench-go](https://github.com/nikki93/raylib-bench-go), Benchmark written in Go.
- [rurush47/ca-particle-system](https://github.com/rurush47/ca-particle-system), Particle system for university project written in C++ using raylib.
- [ProfJski/RayLib-Examples](https://github.com/ProfJski/RayLib-Examples), Some fun math or physics demos made easy with raylib and written in C++.
- [orbisdev/orbisGl2samples](https://github.com/orbisdev/orbisGl2samples), orbisGl2 raylib samples for liborbis (For PlayStation 4).
- [Delvix000/RaylibErosionStandalone](https://github.com/Delvix000/RaylibErosionStandalone), Graphics demo with that features a procedural tropical island and some cool stuff like real-time erosion simulation, reflective-refractive water and animated day/night skybox!
- [Pakz001/Raylib-Examples](https://github.com/Pakz001/Raylib-Examples), Collection of raylib code examples - For learning the C language with 2D and 3D games.
- [ChrisDill/Raylib-cs-Examples](https://github.com/ChrisDill/Raylib-cs-Examples), C# examples for raylib-cs.
- [SasLuca/rayfork-tests](https://github.com/SasLuca/rayfork-tests), Collection of examples written in rayfork that also serve as tests.
- [dtcristo/cray-examples](https://github.com/dtcristo/cray-examples), raylib examples ported to Crystal.
- [raysan5/raylib-games](https://github.com/raysan5/raylib-games), raysan5's collection of games made with raylib.
- [Rabios/rayfork-games](https://github.com/Rabios/rayfork-games), Full port of raylib sample games to rayfork!
- [WEREMSOFT/c99-raylib-car-physics](https://github.com/WEREMSOFT/c99-raylib-car-physics), Car physiscs made with raylib.
- [WEREMSOFT/c99-raylib-shadowmap](https://github.com/WEREMSOFT/c99-raylib-shadowmap), Shadowmap implementation in raylib.
- [rillk500/Dlang-Game-Dev](https://github.com/rillk500/Dlang-Game-Dev), Games created with D programming language.
- [rillk500/Learn-Dlang-game-dev](https://github.com/rillk500/Learn-Dlang-game-dev), Learn D programming language by creating games!
- [BitPuffin/zig-raylib-experiments](https://github.com/BitPuffin/zig-raylib-experiments), Some classic game implementations in Zig using raylib.
- [MetlHedd/raylib-rs-examples](https://github.com/MetlHedd/raylib-rs-examples), Collection of raylib examples written in Rust using raylib-rs.
- [DaNiKhan-GbR/Dnkvw-Raylib-Example](https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Example), Virtual window raylib 3D Example.
- [Demizdor/rlexp](https://github.com/Demizdor/rlexp), Experiments using the raylib library.
- [fr3fou/tic-tac-toe-ai](https://github.com/fr3fou/tic-tac-toe-ai), Tic-Tac-Toe implementation and AI, using Raylib for the GUI and Minimax + Alpha-Beta pruning for the AI.
- [petuzk/raylib-line-triangulator](https://github.com/petuzk/raylib-line-triangulator), Line triangulation algorithm for raylib.
- [rillk500/clang-game-dev](https://github.com/rillk500/clang-game-dev), Games created with C programming language.
- [ThePituLegend/SmurfInvaders](https://github.com/ThePituLegend/SmurfInvaders), Technical Demo as an explorative project of Raylib. Random game based on Space Invaders and alike.
- [riadafridishibly/recursive-sudoku-viz](https://github.com/riadafridishibly/recursive-sudoku-viz), Recursive sudoku solver visualizer in raylib, Written in C++.
- [amazingchow/through-the-maze](https://github.com/amazingchow/through-the-maze), Through the maze based on raylib + genetic algorithm.
- [GheorgheMorari/RaylibCSGraphs](https://github.com/GheorgheMorari/RaylibCSGraphs), Practical implementation of Linear Transfromation, Written in C#.
- [Sepheus/critter_comforts](https://github.com/Sepheus/critter_comforts), Source code of hit first game from legendary studio Vat O'Coffee. Coded from scratch in the space of a couple of days for the V&A Operas & Bridges GameJam, Written in D.
- [DavinderMaverick/VoronoiDiagram](https://github.com/DavinderMaverick/VoronoiDiagram), Voronoi Diagrams using Fortune's Algo, Written in C++.
- [apahl/corosim](https://github.com/apahl/corosim), Simple infection simulator, written in Swift using Raylib.
- [baylej/tmx](https://github.com/baylej/tmx), C tmx map loader have example uses raylib [here](https://github.com/baylej/tmx/tree/master/examples/raylib)!
- [albertnadal/MandelbrotGoLang](https://github.com/albertnadal/MandelbrotGoLang), Distributed computing Mandelbrot implementation using GoLang, gRPC and RayLib.
- [OnACoffeeBreak/raylib_tiled_import_with_tmx](https://github.com/OnACoffeeBreak/raylib_tiled_import_with_tmx), Example of how to use Raylib to import and display a Tiled map editor file.
- [RobLoach/raylib-meson-sample](https://github.com/RobLoach/raylib-meson-sample), Example of building a raylib application with Meson.
- [MrOneTwo/Raylib-shaders](https://github.com/MrOneTwo/Raylib-shaders), Having fun with shaders.
- [anatagawa/Demo-Paradox](https://github.com/anatagawa/Demo-Paradox), Demo with Raylib.
- [anatagawa/Demo-Interpole](https://github.com/anatagawa/Demo-Interpole), Demo with Raylib.
- [anatagawa/Demo-Awesome](https://github.com/anatagawa/Demo-Awesome), Demo with Raylib.
- [nathhB/nbnet](https://github.com/nathhB/nbnet), nbnet is single header C network library to implement client-server network code for games, Has example for raylib can be found [here](https://github.com/nathhB/nbnet/tree/master/examples/raylib).
- [edomin/Raygui_Helloworld](https://github.com/edomin/Raygui_Helloworld), Example of using Raygui library with tigr graphics library.
- [JohnLins/SphereDensity](https://github.com/JohnLins/SphereDensity), Example of 3D rendered sphere increasing in "density" by increasing the rings and slices.
- [badlydrawnrod/evaluate-raylib](https://github.com/badlydrawnrod/evaluate-raylib), Few short and cross-platform raylib demos. Known to work on Windows, Raspberry Pi 400 (desktop + native), Web (emscripten).
- [c-krit/kraber](https://github.com/c-krit/kraber), Cool ideas and experiments with raylib, Written in C.
- [ArnautDaniel/riley-duper](https://github.com/ArnautDaniel/riley-duper), Iterative melancholy written in Factor.
- [jmorel33/RayLib-Video-Modes](https://github.com/jmorel33/RayLib-Video-Modes), Example of getting list of monitor's video modes from GLFW3 with raylib!
- [TheCatOverlord/Raylib-Joystick](https://github.com/TheCatOverlord/Raylib-Joystick), Example implementing Joystick input for raylib using `<linux/joystick.h>`.
- [tomxmm0/dvd_screensaver](https://github.com/tomxmm0/dvd_screensaver), DVD Screensaver made with raylib.
- [Razikus/raylib-qrcode](https://github.com/Razikus/raylib-qrcode), QR Code generator for raylib using [nayuki/QR-Code-generator](https://github.com/nayuki/QR-Code-generator).
- [zvoskars/keyListener](https://github.com/zvoskars/keyListener), Program that follows key inputs using C++ and the raylib library for Trackmania.
- [senior-sigan/simple_games](https://github.com/senior-sigan/simple_games), Games created during live-streams by Ilya Siganov.
- [ValiantInteractive/FPS-engine-raylib](https://github.com/ValiantInteractive/FPS-engine-raylib), FPS game engine and simple First Person Shooter created with raylib using the C language.
- [PixelPhobicGames/Chrome-Dino-game-ripoff-](https://github.com/PixelPhobicGames/Chrome-Dino-game-ripoff-), Chrome Dinosaur game written in C using raylib.
- [MrOneTwo/Raylib-shaders](https://github.com/MrOneTwo/Raylib-shaders), C++ Example(s) for having fun with shaders.
- [nas-programmer/raylib_projects](https://github.com/nas-programmer/raylib_projects), Things made with raylib and C++.
- [NevilleJS/spirograph](https://github.com/NevilleJS/spirograph), Spirograph made in C++ using raylib.
- [someone-existing/Worley-noise-raylib](https://github.com/someone-existing/Worley-noise-raylib), Extremely slow and buggy implementation of Worley noise done in rayLib and C++.
- [Rledrin/PathFinding](https://github.com/Rledrin/PathFinding), C++ PathFinding example for raylib.
- [Rledrin/RayCasting2D](https://github.com/Rledrin/RayCasting2D), C++ Raycasting example for raylib.
- [nezvers/Raylib_TrueTileCollision](https://github.com/nezvers/Raylib_TrueTileCollision), Retro platformer collision paired with modern approach utilizing delta time.
- [justinac0/raylib-raycaster](https://github.com/justinac0/raylib-raycaster), Basic raycaster implementation in C using faylib for rendering.
- [RafaelOliveira/raylib-bunnymark](https://github.com/RafaelOliveira/raylib-bunnymark), Simple Bunnymark test with raylib.
- [henriquel1997/webcam_raylib](https://github.com/henriquel1997/webcam_raylib), Test program that displays a webcam feed into a window and uses ESCAPI and raylib.
- [yaram/match-three](https://github.com/yaram/match-three), C++ Simple match-three prototype using raylib.
- [erikerlandson/ray-odh-demo](https://github.com/erikerlandson/ray-odh-demo), Prototype an integration of ray with Open Data Hub, using a singleuser profile to provision a ray cluster.
- [neonmoe/metro](https://github.com/neonmoe/metro), Raymarched exploration of floating-point errors in a metro tunnel.
- [afreytes/RLSolarSystem](https://github.com/afreytes/RLSolarSystem), Solar system simulation based on [arinal/WPFSolarSystem](https://github.com/arinal/WpfSolarSystem) but swapping WPF for raylib using [ChrisDill/Raylib-cs](https://github.com/ChrisDill/Raylib-cs) bindings for C#.
- [Adobe-Android/raylib-demo](https://github.com/Adobe-Android/raylib-demo), raylib demo project using C++ and CMake.
- [PHILLIPGATLIN/Caption](https://github.com/PHILLIPGATLIN/Caption), Image captioning program made with raylib.
- [adamszymanowski/RayLibExamples](https://github.com/adamszymanowski/RayLibExamples), raylib 3.5 examples.
- [gihadmecha/raylib_examples_to_learn](https://github.com/gihadmecha/raylib_examples_to_learn), Some raylib examples.
- [danimartin82/rayMaschine](https://github.com/danimartin82/rayMaschine), Project for the raylib 32x32 Competition.
- [JusticeShultz/RaylibPhysics](https://github.com/JusticeShultz/RaylibPhysics), Physics in C++.
- [pintertamas/my-awesome-project](https://github.com/pintertamas/my-awesome-project), Programming homework that uses the raylib library for graphics.
- [bruhmoment3124/raylib](https://github.com/bruhmoment3124/raylib), Things made with raylib.
- [feihong/gamedev-experiments](https://github.com/feihong/gamedev-experiments), [Feihong](https://github.com/feihong)'s raylib quickstart.
- [creikey/raylib-particles](https://github.com/creikey/raylib-particles), Particles life made in raylib.
- [t0rre/Raylib-3d-Test](https://github.com/t0rre/Raylib-3d-Test), Test with 3D in raylib.
- [JohnLins/GravitationalAcceleration](https://github.com/JohnLins/GravitationalAcceleration), Example(s) for gravity with acceleration!
- [Nuuttif/2x2RubiksCubeSimulator](https://github.com/Nuuttif/2x2RubiksCubeSimulator), WIP 2x2 Rubik's cube simulator.
- [DoctorAkula/Altair8800](https://github.com/DoctorAkula/Altair8800), Front panel emulation of the MITS Altair 8800 written in C using the raylib library.
- [fullnitrous/rsim](https://github.com/fullnitrous/rsim), Cross platform rocket simulation software package written in C with raylib.
- [jessp/Pepper-s-Pi-Cone](https://github.com/jessp/Pepper-s-Pi-Cone), WIP repository to adapt Roxanne Luo's Pepper's cone into C with Raylib with the intention of running it off a Raspberry Pi.
- [Nachasic/vicarious-rs](https://github.com/Nachasic/vicarious-rs), Gamedev experiments with raylib and Rust.
- [buribalazs/raylib-rs-play_sound_multi](https://github.com/buribalazs/raylib-rs-play_sound_multi), Example to demonstrate a crash on windows 10 written in Rust.
- [teh-cmc/rts](https://github.com/teh-cmc/rts), Building an RTS the old way, with Rust, raylib & Emscripten.
- [jestarray/raylib_ffi_bug](https://github.com/jestarray/raylib_ffi_bug), Incorrect FFI call which turning bool to a random number, Written in Rust.

### Templates

- [irskep/raylibtest](https://github.com/irskep/raylibtest), raylib Nim bindings test example.
- [jamiltron/ray-starter](https://github.com/jamiltron/ray-starter), Skeleton of a raylib project with CMake.
- [benweidig/raylib-template](https://github.com/benweidig/raylib-template), Linux template for raylib.
- [CapsCollective/raylib-cpp-starter](https://github.com/CapsCollective/raylib-cpp-starter), Portable and automated template for raylib projects with C++ bindings.
- [inque/simple_raylib_template](https://gitlab.com/inque/simple_raylib_template), This is a simple raylib boilerplate that can be used as a starting point for raylib, It has also utility to build for Web!
- [oswjk/raylib-imgui-template](https://github.com/oswjk/raylib-imgui-template), Basic raylib + Dear ImGui template.
- [AIE-Seattle-Prog/raygame](https://github.com/AIE-Seattle-Prog/raygame), Sample C++ project setup with raylib for Visual Studio 2017.
- [AIE-Seattle-Prog/raygamecsharp](https://github.com/AIE-Seattle-Prog/raygamecsharp), Sample C# project setup with raylib-cs for Visual Studio 2017.
- [DaNiKhan-GbR/Dnkvw-Raylib-Minimal-Example](https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Minimal-Example), Minimal example that demonstrates the usage of Dnkvw with Raylib. It can be used as a project template.
- [krzosa/RaylibHotReloadTemplate](https://github.com/krzosa/RaylibHotReloadTemplate), Template for hot reload code in raylib.
- [WEREMSOFT/c99-raylib-template](https://github.com/WEREMSOFT/c99-raylib-template), Starting template to work with raylib, Uses make for build.
- [WEREMSOFT/c99-raylib-cimgui-template](https://github.com/WEREMSOFT/c99-raylib-cimgui-template), Simple template to integrate raylib with imgui on C99, Uses cimgui bindings.
- [WEREMSOFT/raylib-network-template](https://github.com/WEREMSOFT/raylib-network-template), Kinda serverless multiplayer template. It can be used to make a very basic multiplayer game.
- [SasLuca/raylib-cmake-template](https://github.com/SasLuca/raylib-cmake-template), Very minimal project template for raylib using CMake that works well in CLion & Visual Studio.
- [SasLuca/rayfork-sokol-template](https://github.com/SasLuca/rayfork-sokol-template), Simple rayfork project template with sokol-app and CMake.
- [RaniSputnik/go-raylib-template](https://github.com/RaniSputnik/go-raylib-template), Starter template for building games with the raylib Golang bindings. 
- [Hidden-Pixel/raylib-starter-kit](https://github.com/Hidden-Pixel/raylib-starter-kit), This repository is to raylib starter kit to help get up and running quickly after installing MSVC, clang or gcc, and emcc.
- [oswjk/rayskeleton](https://github.com/oswjk/rayskeleton), Skeleton project template for raylib. Uses CMake.
- [braedenf/RaylibStarterProjectXcode](https://github.com/braedenf/RaylibStarterProjectXcode), Basic window implemented with raylib in XCode.
- [jacmoe/raystart](https://github.com/jacmoe/raystart), Quick CMake based project template for exploratory graphics programming using raylib.
- [JamieMair/RaylibVSTemplate](https://github.com/JamieMair/RaylibVSTemplate), Template Visual Studio 2019 C++ project for the raylib library.
- [Yrds/raylib-boilerplate](https://github.com/Yrds/raylib-boilerplate), out-of-box environment to develop raylib games.
- [Qinbeans/raylib_graphic_template](https://github.com/Qinbeans/raylib_graphic_template), Template for future use and has working adjustable resolution.
- [CodingCor/tempraylib](https://github.com/CodingCor/tempraylib), Simple C++ template to use raylib in Linux and Windows.
- [MrOneTwo/Raylib-Scons-boilerplate](https://github.com/MrOneTwo/Raylib-Scons-boilerplate), Boilerplate for raylib with Scons as build system.
- [gilzoide/raylib-meson-template](https://github.com/gilzoide/raylib-meson-template), Minimal template project for C/C++ applications using raylib built using Meson.
- [Ushio/raylibMinimumVS](https://github.com/Ushio/raylibMinimumVS), Simple C++ template for raylib for use with Visual Studio 2017.
- [janderkkotlarski/raylib_template](https://github.com/janderkkotlarski/raylib_template), C++ Simple raylib template that should works when raylib is correctly installed.
- [Lattay/raylib-lsk](https://github.com/Lattay/raylib-lsk), Lattay's Starter Kit for raylib, small boiler plate for raylib projects.
- [charlesmartinreed/vscode-raylib-base](https://github.com/charlesmartinreed/vscode-raylib-base), Setup used by GamesFromScratch when he made tutorials for raylib.
- [AIESydProgYr12021/RaylibCSharpStarter](https://github.com/AIESydProgYr12021/RaylibCSharpStarter), raylib C# game starter kit.
- [LodisAIE/RaylibStarterCPP](https://github.com/LodisAIE/RaylibStarterCPP), raylib C++ game starter kit.
- [HeatXD/Raylib-with-Flecs-Template](https://github.com/HeatXD/Raylib-with-Flecs-Template), Template for raylib with a custom flecs pipline for raylib.
- [dwperrin/raylib-template-vscode](https://github.com/dwperrin/raylib-template-vscode), VSCode template for raylib!
- [underscorenygren/parsec_raylib_template](https://github.com/underscorenygren/parsec_raylib_template), Starter project for the parsec and raylib integration article series, Use this as a base from which to create your own games.
- [LeHaine/kotlin-native-raylib-starter](https://github.com/LeHaine/kotlin-native-raylib-starter), Base projected configured to link, build, and run raylib with Kotlin Native.
- [JustinKatic/Raylib-C-starterProj](https://github.com/JustinKatic/Raylib-C-starterProj), Basic startup setup for raylib with a clear Start and Update function.
- [ruscito/raylib_template](https://github.com/ruscito/raylib_template), raylib template for MacOS.
- [waruqi/raylib-scaffold](https://github.com/waruqi/raylib-scaffold), Minimal raylib project template that uses XMake.
- [GoldenbergDaniel/RayTemplateC](https://github.com/GoldenbergDaniel/RayTemplateC), Template for the raylib library in C.

### Articles

- [raylib game coding library for C](http://bedroomcoders.co.uk/raylib-game-coding-library-for-c)
- [raylib novices guide for creating a simple game](http://bedroomcoders.co.uk/raylib-a-novices-guide-for-creating-a-simple-game)
- [Creating a simple game (part 2)](http://bedroomcoders.co.uk/creating-a-simple-game-part-2)
- [Creating a simple game (part 3)](http://bedroomcoders.co.uk/creating-a-simple-game-part-3)
- [Creating a simple game (part 4)](http://bedroomcoders.co.uk/creating-a-simple-game-part-4)
- [Creating a simple game (part 5) finishing up](http://bedroomcoders.co.uk/creating-a-simple-game-part-5-finishing-up)
- [Complete Template for Raylib](http://bedroomcoders.co.uk/complete-template-for-raylib)
- [3d Physics with raylib and ODE](http://bedroomcoders.co.uk/3d-physics-with-libray-and-ode)
- [raylib adding a static terrain (ODE)](http://bedroomcoders.co.uk/raylib-adding-a-static-terrain-ode)
- [Looking again at compiling a Windows Raylib app](http://bedroomcoders.co.uk/looking-again-at-compiling-a-windows-raylib-app)
- [Creating a 64 bit executable with raylib on windows](http://bedroomcoders.co.uk/creating-a-64-bit-executable-with-raylib-on-windows)
- [Aiming at moving targets…](http://bedroomcoders.co.uk/aiming-at-moving-targets)
- [Aiming at 3d moving targets](http://bedroomcoders.co.uk/aiming-at-3d-moving-targets)
- [Painting on a 3d Mesh with Raylib](http://bedroomcoders.co.uk/painting-on-a-3d-mesh-with-raylib)
- [Raylib, projecting 3D onto 2D handy for debugging](http://bedroomcoders.co.uk/raylib-projecting-3d-onto-2d-handy-for-debugging)
- [Raylib and Chipmunk2d](http://bedroomcoders.co.uk/raylib-and-chipmunk2d)
- [PhysFS and raylib](http://bedroomcoders.co.uk/physfs-and-raylib)
- [Using libmpeg2 with RayLib](http://bedroomcoders.co.uk/using-libmpeg2-with-raylib)
- [Aligning a model with a terrain (raylib)](http://bedroomcoders.co.uk/aligning-a-model-with-a-terrain-raylib)
- [A simple maze creation algorithm (C99 and raylib)](http://bedroomcoders.co.uk/a-simple-maze-creation-algorithm-c99-and-raylib)
- [Using RayLib with an ECS](http://bedroomcoders.co.uk/using-raylib-with-an-ecs)
- [Animating sky with raylib](http://bedroomcoders.co.uk/animating-sky-with-raylib)
- [raylib Fog](http://bedroomcoders.co.uk/raylib-fog)
- [Sprite Sheets with RayLib](http://bedroomcoders.co.uk/sprite-sheets-with-raylib)
- [Shaders with raylib](http://bedroomcoders.co.uk/shaders-with-raylib)
- [Lighting with raylib](http://bedroomcoders.co.uk/lighting-with-raylib)
- [2D Spotlight shader with RayLib](http://bedroomcoders.co.uk/2d-spotlight-shader-with-raylib)
- [Implementing a 3d GUI with raylib](http://bedroomcoders.co.uk/implementing-a-3d-gui-with-raylib)
- [Creating Raspberry Pi applications with Raylib and Ruby (Part 1)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-fba3d35b2877)
- [Creating Raspberry Pi applications with Raylib and Ruby (Part 2)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-part-ii-edc47680157b)
- [Ubuntu 18.04 için Raylib kurulumu (Turkish)](https://medium.com/@msoygen/ubuntu-18-04-raylib-kurulumu-8ff9c4274b91)
- [raylib: 6 years of fun](https://gist.github.com/raysan5/04a2daf02aa2a6e79010331f77bf983f)
- [rGuiIcons Making Of Diary](https://gist.github.com/raysan5/fe769f77b43b6c612600166498ce3640)

### Resources and Links

- [What raylib uses?](https://github.com/raysan5/raylib/wiki/raylib-dependencies)
- [raylib Official Cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)
- [raylib Official examples](https://www.raylib.com/examples.html)
- [raylib Official Wiki](https://github.com/raysan5/raylib/wiki)
- [raylib on Wikipedia](https://en.wikipedia.org/wiki/Raylib)
- [raylib website](https://raylib.com)
- [raylib YouTube channel](https://www.youtube.com/channel/UC8WIBkhYb5sBNqXO1mZ7WSQ)
- [raylib Discord channel](https://discord.gg/VkzNHUE)
- [raylib on Reddit](https://www.reddit.com/r/raylib)
- [raylib on Handmade](https://raylib.handmade.network)
- [raylib page on itch.io](https://raysan5.itch.io/raylib)

> Can't find your awesome stuff? Make issue or pull request for that!

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

Credits
1. https://github.com/JiahaoYao/awesome-ray
