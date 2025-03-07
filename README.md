# Mermaid Diagrams Repository

Welcome to the **Mermaid Diagrams Repository**! This collection contains richly detailed Mermaid diagrams illustrating various technical processes and architectures. From compiler workflows to cloud architectures, these diagrams provide visual insights into complex systems using the powerful Mermaid diagramming language.

## 🔍 Diagrams Overview

This repository contains the following enhanced Mermaid diagrams:

### System Architecture
- `simple_webapp.mermaid` - Three-tier web application architecture with AWS components
- `complex_web_app.mermaid` - Comprehensive cloud architecture for enterprise applications
- `k8s_architecture.mermaid` - Kubernetes component architecture showing control and data planes

### Process Flows
- `k8s_journey.mermaid` - Complete lifecycle of `kubectl apply` from user to container creation
- `linux_boot.mermaid` - Detailed Linux boot sequence from BIOS to user login
- `linux_process_journey.mermaid` - Process lifecycle in the Linux kernel
- `linux_process_w_threads_journey.mermaid` - Thread management in Linux processes
- `linux_scheduler.mermaid` - Linux kernel scheduler operation

### Networking & Security
- `ssl.mermaid` - TLS/SSL handshake flow with modern cryptographic details
- `saml.mermaid` - SAML authentication and authorization sequence
- `vpn.mermaid` - VPN tunneling and encapsulation process
- `dhcp_dns.mermaid` - Network address configuration and name resolution flow

### Software Execution
- `compiler.mermaid` - Compilation phases from source code to executable
- `container_linux_journey.mermaid` - Container lifecycle from image to running process
- `java_program_journey.mermaid` - Java execution flow through JVM
- `python_program_journey.mermaid` - Python program execution process

## ✨ Features

These diagrams incorporate several enhanced features:

- **Consistent Theming** - Color palettes tailored to diagram type (Kubernetes blue, AWS orange, etc.)
- **Visual Hierarchy** - Logical grouping with subgraphs and directional flow
- **Component Icons** - Emoji icons indicate component types (👤 users, 💾 storage, etc.)
- **Technical Details** - Protocol specifications, version details, and alternative paths
- **Phase Separation** - Clear process stages with colored backgrounds
- **Comprehensive Comments** - Well-documented code with section explanations

## 🚀 How to Use

### Viewing Diagrams

Several options are available:

1. **VS Code Extension**: Install the [Mermaid Preview](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) extension

2. **Mermaid CLI**: Render diagrams to images using the Mermaid CLI:
   ```bash
   npx @mermaid-js/mermaid-cli mmdc -i file.mermaid -o output.png
   ```

3. **Online Editors**: Use the [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/)

4. **HTML Preview**: Generate an HTML file for local viewing:
   ```bash
   echo "<!DOCTYPE html><html><head><script src='https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js'></script></head><body><pre class='mermaid'>$(cat file.mermaid)</pre><script>mermaid.initialize({startOnLoad:true});</script></body></html>" > preview.html
   ```

### Making Changes

When modifying or adding diagrams, please follow the style guide in [CLAUDE.md](./CLAUDE.md) for consistent styling and organization.

## 🤝 Contributing

Your contributions are welcome! To contribute:

1. **Fork the repository** to your GitHub account
2. **Create a branch** for your changes
3. **Make your updates** following the style guide in CLAUDE.md
4. **Submit a pull request** with a clear description of your changes

## 📝 Style Guide

See [CLAUDE.md](./CLAUDE.md) for detailed styling guidelines, including:

- Theme configuration and color palettes
- Component visualization standards
- Diagram organization principles
- Technical detail requirements

## 📜 License

This repository is shared under the MIT License. Feel free to use, modify, and share any of the diagrams as you see fit.