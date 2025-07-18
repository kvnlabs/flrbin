# ShareBin Roadmap
## Fix
- [ ] history page 

## Core Features
- [x] Cloudflare Worker and KV storage
- [x] Edit history and revisions
- [x] fix spacing in between elements
- [x] Add Navbar
- [x] Add Views count
- [x] Customizable paste expiration
- [ ] Add Share, raw copy, download buttons in menu
- [ ] show the language used in codeblock 
- [ ] image render, embedded video preview
- [ ] Proper Keyboard Shortcuts

## Future Roadmap (v2.0+)

### 🚀 Modern Markdown Engine
- [ ] **Multi-Syntax Support**:
  - [x] GitHub Flavored Markdown (GFM)
  - [x] Add copy button to code block
  - [ ] Math equations (KaTeX/MathJax)
  - [ ] Mermaid diagrams support
  - [x] Definition lists, footnotes, and task lists
  - [ ] Custom syntax extensions (callouts, admonitions)
- [x] **Advanced Parser**: Replace marked.js with unified/remark
  - [x] AST-based processing for better extensibility
  - [x] Plugin ecosystem for custom transformations
  - [x] Better error handling and validation

### 🔒 Security & Privacy
- [x] **Encryption Support**
  - [x] Server-side encryption with AES-256-GCM
  - [x] Password-protected pastes with industry-standard encryption
  - [x] Secure key derivation using PBKDF2 (100,000 iterations)
  - [x] Zero-knowledge architecture - passwords never stored
- [ ] **Access Control**
  - [x] View-only links with login
  - [x] View-only passwords (separate from edit codes)
  - [x] Expiration dates with automatic cleanup
  - [ ] Rate limiting and abuse protection
  - [ ] IP-based access restrictions

### ✨ Enhanced Editor Experience
- [ ] **Editor Interface**
  - [x] Enhanced CodeMirror with keyboard shortcuts
  - [x] Visual toolbar for common formatting
  - [x] Live preview with real-time updates
- [ ] **Enhanced Preview**
  - [x] Real-time markdown rendering
  - [x] Support for all new features
  - [ ] PDF export capabilities
  - [ ] Social media preview cards

### 🎨 Modern UI/UX
- [x] **Design System**
  - [x] Enhanced CSS with better typography and spacing
  - [x] Improved dark/light theme support
  - [x] Modern component styling
  - [x] Consistent design language
- [x] **Typography & Fonts**
  - [x] Improved font stacks and typography scales
  - [x] Better reading experience
  - [x] Enhanced code block styling

### 🏗️ Infrastructure
- [ ] **Self-hosting Options**
  - [ ] Docker Compose setup
- [ ] **Performance**
  - [ ] CDN integration for global speed
  - [ ] Lazy loading for large documents
  - [ ] Service workers for offline functionality