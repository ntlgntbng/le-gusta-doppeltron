# **Contributing Guidelines**

Thank you for your interest in contributing to this project\! We welcome contributions from developers, audio engineers, and open-source enthusiasts of all skill levels.

## **Table of Contents**

* [Code of Conduct](#bookmark=id.illyvhy3nal7)  
* [How Can I Contribute?](#bookmark=id.p61l8m8wv46o)  
  * [Reporting Bugs](#bookmark=id.iijn3mn9iwuj)  
  * [Suggesting Enhancements](#bookmark=id.n77xc78lk5d0)  
  * [Pull Request Process](#bookmark=id.llkzmuid7vpe)  
* [Commit Message Guidelines](#bookmark=id.g6i96tc00t3c)  
* [Development & Technical Standards](#bookmark=id.v5cgnvuzaclt)

## **Code of Conduct**

This project and everyone participating in it is governed by our [Code of Conduct](http://docs.google.com/CODE_OF_CONDUCT.md). By contributing, you are expected to uphold these standards. Please report unacceptable behavior to the project maintainer.

## **How Can I Contribute?**

### **Reporting Bugs**

Before creating a bug report, please check the existing GitHub Issues to ensure the problem hasn't already been reported.

When opening a bug report, include as many details as possible:

* **Clear, Descriptive Title:** Summarize the issue succinctly.  
* **Steps to Reproduce:** Provide a numbered list of exact steps taken to trigger the bug.  
* **Expected vs. Actual Behavior:** Describe what you expected to happen versus what actually occurred.  
* **Environment Details:** Include browser name/version, operating system, display scale factor (e.g., Retina/4K), and audio output device.  
* **Console Logs:** Include relevant error messages from browser Developer Tools (F12).

### **Suggesting Enhancements**

Enhancement requests are tracked as GitHub Issues. When proposing a new feature or telemetry module:

* Use a clear, descriptive title.  
* Explain the practical use case and acoustic or technical rationale behind the enhancement.  
* Describe the expected workflow or UI/UX behavior.

### **Pull Request Process**

1. **Fork the Repository:** Create your own copy of the repository on GitHub.  
2. **Clone & Branch:**  
   git clone \[https://github.com/YOUR-USERNAME/le-gusta-doppeltron.git\](https://github.com/YOUR-USERNAME/le-gusta-doppeltron.git)  
   cd le-gusta-doppeltron  
   git checkout \-b feature/your-feature-name

3. **Develop & Test:** Implement your changes and test thoroughly across multiple screen sizes and browsers.  
4. **Commit Changes:** Use structured commit messages following our convention below.  
5. **Push & Open PR:**  
   git push origin feature/your-feature-name

   Submit your Pull Request against the main branch with a summary of changes and reference any related issue numbers.

## **Commit Message Conventions**

We follow the **Conventional Commits** specification (type(scope): description):

| Commit Type | Description |
| :---- | :---- |
| feat | A new feature or hardware telemetry module |
| fix | A bug fix (e.g., AudioContext state, canvas DPI scale bugs) |
| docs | Documentation changes only |
| style | Code formatting changes without behavior modification |
| refactor | Code restructuring without altering functionality |
| perf | Performance optimizations (e.g., canvas rendering efficiency) |

*Example:*

feat(dsp): add smooth audio gain ramping to eliminate oscillator clicks  
