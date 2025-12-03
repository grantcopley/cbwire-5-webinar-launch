# 🚀 CBWIRE 5 Live Launch Webinar

Welcome to the CBWIRE 5 Live Launch Webinar demonstration repository! This repo contains working examples of CBWIRE's powerful features and the exciting new capabilities introduced in version 5.

## 🎯 What is CBWIRE?

CBWIRE is a reactive framework for ColdBox that brings the power of Livewire to CFML and BoxLang applications. Build modern, reactive interfaces with server-side rendering and minimal JavaScript.

📚 **Documentation**: [https://cbwire.ortusbooks.com/](https://cbwire.ortusbooks.com/)

## 🚀 Running This Repository

To run this demo application, you need [CommandBox](https://www.ortussolutions.com/products/commandbox) installed.

```bash
box server start
```

Your application will be available at `http://localhost:3000`

## 🔍 Explore the Examples

This repository contains practical demonstrations of CBWIRE features. Each example is a working wire component you can explore and learn from.

### 🌟 Getting Started Examples

**What is CBWIRE / Livewire?**
- `app/wires/Greeter.bxm` - Basic wire:click example
- `app/wires/GreeterAlpine.bxm` - Alpine.js integration with $wire
- `app/wires/GreeterAlpineTransition.bxm` - Alpine.js transitions with CBWIRE

### 🆕 New Features in CBWIRE 5

**BoxLang Support**
- Full BoxLang compatibility with `.bxm` single file components
- `@extends` for single file components
- All examples use BoxLang syntax with `<bx:output>` and `<bx:script>` sections

**Security Features**
- `app/wires/AdminPanel.bxm` - onSecure lifecycle method demonstration
  - Wire mounting with parameters: `#wire( "AdminPanel", { userId: 50 } )#`
  - secureMountFailMessage customization
  - cbsecurity annotations integration
  - Enhanced CSRF protection

**Data Property Enhancements**
- `app/wires/DotNotationWire.bxm` - Dot notation data properties
- `app/wires/LockedPropertiesWire.bxm` - Locked properties for security

**Developer Experience**
- `app/wires/LazyWire.bxm` - Lazy loading with `lazy = true`
- `app/wires/EventObjectWire.bxm` - Direct event object access in templates
- Folder organization support: `wires/subfolder/` structure

**Livewire v3.6.4 Directives**
- `wire:current` - Current state tracking
- `wire:cloak` - Hide elements until CBWIRE loads
- `wire:show` - Conditional visibility
- `wire:text` - Text content binding
- `wire:replace` - Replace element content
- `wire:model.blur` - Update on blur event

**Form Handling**
- `app/wires/SimpleForm.bxm` - Professional form with cbvalidation

### 🏆 Honorable Mentions

- **File Uploads** - Built-in support for reactive file uploads
- **CBWIRE CLI** - [https://github.com/mrigsby/cbwire-cli](https://github.com/mrigsby/cbwire-cli) - Command-line tools for CBWIRE development

## 🚀 Installation

Install CBWIRE 5 in your ColdBox application:

```bash
box install cbwire@5
```

## 📚 Resources

- **CBWIRE Documentation**: [https://cbwire.ortusbooks.com/](https://cbwire.ortusbooks.com/)
- **GitHub Repository**: [https://github.com/coldbox-modules/cbwire](https://github.com/coldbox-modules/cbwire)
- **CBWIRE CLI**: [https://github.com/mrigsby/cbwire-cli](https://github.com/mrigsby/cbwire-cli)

## 💬 Questions?

Join us for the live webinar Q&A, or reach out to the CBWIRE community for support!

---

**Built with ❤️ by Grant Copley**
