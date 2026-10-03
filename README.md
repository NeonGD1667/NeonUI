# NeonUI

> Lightweight, modern and beautiful cross-language UI framework built in C.

NeonUI is a lightweight UI framework written in C, designed to provide a simple, modern, and beautiful interface while keeping the core small and portable.

The project is being developed with a long-term goal of supporting multiple programming languages through a stable C API.

## 🚧 Status

**Early Development — Not production ready**

NeonUI is currently under active development.

The core architecture, input system, layout system, renderer abstraction, widgets, animation system, and backend support are being developed step by step.

APIs may change frequently during this stage.

## 🤝 Contributing

NeonUI is currently looking for developers who are interested in helping build the framework.

Contributions are welcome through **Pull Requests**.

You can help with:

* Core C development
* Input handling
* Layout system
* Widget development
* Rendering
* Animation
* Backend development
* CMake/build system
* Documentation
* Testing and bug fixing

If you want to contribute, fork the repository, make your changes, and open a Pull Request.

Large architectural changes should be discussed before implementation.

## 🛠️ Development

NeonUI is being built with:

* **C** — Core framework
* **CMake** — Build system
* **C23** — Target language standard
* **C++** — Optional future wrapper
* **C# / Java** — Planned language bindings

The core is intentionally kept independent from any specific engine or application.

## 🗺️ Roadmap

### Phase 1 — Core

* [ ] Core context
* [ ] Memory management
* [ ] ID system
* [ ] Basic geometry types
* [ ] Mouse input
* [ ] Keyboard input
* [ ] Focus system
* [ ] Event system
* [ ] Layout system
* [ ] Widget state
* [ ] Renderer abstraction
* [ ] Animation system

### Phase 2 — UI

* [ ] Text rendering
* [ ] Rounded rectangles
* [ ] Panels
* [ ] Buttons
* [ ] Checkboxes
* [ ] Toggles
* [ ] Sliders
* [ ] Text input
* [ ] Scrolling
* [ ] Popups
* [ ] Tabs
* [ ] Themes
* [ ] Fonts

### Phase 3 — Backends

* [ ] Renderer backend
* [ ] Neon Cocos
* [ ] Cocos2d-x integration
* [ ] Geode integration
* [ ] Input backend
* [ ] Font/texture backend

### Phase 4 — Stabilization

* [ ] Performance optimization
* [ ] Memory optimization
* [ ] Unicode support
* [ ] DPI scaling
* [ ] Animation improvements
* [ ] Accessibility basics
* [ ] Debug tools
* [ ] Documentation
* [ ] Examples
* [ ] API cleanup

### Phase 5 — Public API

* [ ] Stable C API
* [ ] Stable ABI
* [ ] Public handles
* [ ] Error handling
* [ ] API versioning
* [ ] `neon-ui.h`

> `neon-ui.h` will be finalized after the underlying systems are stable.

### Phase 6 — Language Bindings

* [ ] C++ wrapper
* [ ] C# bindings
* [ ] Java bindings
* [ ] Additional language bindings

### Phase 7 — NeonUI 1.0

* [ ] Multiple backends
* [ ] Package/distribution system
* [ ] Documentation website
* [ ] Performance benchmarks
* [ ] Stable API
* [ ] `1.0.0` release

## 🎯 Long-Term Vision

NeonUI aims to become a small, beautiful, and easy-to-use UI framework that developers can integrate into different projects without depending on a large UI engine.

The core will remain written in C, while other languages can interact with NeonUI through its stable C API.

```text
                NeonUI Core
                    │
              Stable C API
             ┌──────┼──────┐
             │      │      │
            C++    C#     Java
             │      │      │
          Wrapper P/Invoke JNI/FFM
```

The long-term goal is simple:

**Easy to use like a simple immediate-mode UI library, but modern, beautiful, lightweight, and extensible.**

## 📄 License

NeonUI is licensed under the Boost Software License 1.0.
