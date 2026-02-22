# iOS + AI Open Source Contribution Guide

A curated list of iOS projects with AI/ML integration perfect for contributing and learning.

---

## 🎯 Why Contribute to iOS + AI Projects?

- Learn cutting-edge CoreML and ML integration
- Work with state-of-the-art models (Stable Diffusion, Transformers, Audio ML)
- Build portfolio with real-world AI applications
- Collaborate with major companies (Hugging Face, etc.)
- Unlock GitHub achievements (Pull Shark, Open Sourcerer)

---

## 🔥 Top iOS + AI Projects to Contribute To

### **1. FluidAudio** ⭐ 1,529+ stars
**Repository**: https://github.com/FluidInference/FluidAudio

**Description**: Frontier CoreML audio models — text-to-speech, speech-to-text, voice activity detection, and speaker diarization in Swift.

**Tech Stack**:
- Swift
- CoreML
- Audio ML models
- State-of-the-art open source

**Open Issues**:
- [Model Support Requests](https://github.com/FluidInference/FluidAudio/issues/49)

**Good For**:
- Audio ML integration
- Modern Swift practices
- Real-world AI applications

**Difficulty**: Medium

---

### **2. Swift CoreML Diffusers (Hugging Face)** ⭐ 2,737+ stars
**Repository**: https://github.com/huggingface/swift-coreml-diffusers

**Description**: Swift app demonstrating CoreML Stable Diffusion for AI image generation on iOS/macOS.

**Tech Stack**:
- Swift
- SwiftUI
- CoreML
- Stable Diffusion
- Hugging Face models

**Open Issues**:
- [How to use in own Swift project](https://github.com/huggingface/swift-coreml-diffusers/issues/102) - Documentation
- [Where to put pretrained models](https://github.com/huggingface/swift-coreml-diffusers/issues/98) - Documentation
- [Pipeline loading errors](https://github.com/huggingface/swift-coreml-diffusers/issues/99) - Bug fix

**Good For**:
- Learning Stable Diffusion
- Working with Hugging Face
- Documentation contributions
- Image generation AI

**Difficulty**: Medium-Hard

---

### **3. CoreMLHelpers** ⭐ 1,428+ stars
**Repository**: https://github.com/hollance/CoreMLHelpers

**Description**: Types and functions that make it easier to work with CoreML in Swift. Widely used foundation library.

**Tech Stack**:
- Swift
- CoreML
- Image processing
- Metal Performance Shaders

**Open Issues**:
- [MacOS support for PixelBuffer](https://github.com/hollance/CoreMLHelpers/issues/47) - Feature
- [Add transpose support for int/float](https://github.com/hollance/CoreMLHelpers/issues/51) - Enhancement
- [Change image to multiArray for TFLite models](https://github.com/hollance/CoreMLHelpers/issues/53) - Feature

**Good For**:
- Foundation library experience
- CoreML utilities
- Cross-platform (iOS/macOS) development

**Difficulty**: Medium

---

### **4. MochiDiffusion** ⭐ 7,841+ stars
**Repository**: https://github.com/MochiDiffusion/MochiDiffusion

**Description**: Run Stable Diffusion on Mac natively with CoreML optimization.

**Tech Stack**:
- Swift
- SwiftUI
- CoreML
- Stable Diffusion
- macOS/iOS

**Good For**:
- Very popular project
- Active development
- Native Mac AI applications
- Modern SwiftUI

**Difficulty**: Medium-Hard

---

### **5. Swift AI** ⭐ 6,066+ stars
**Repository**: https://github.com/Swift-AI/Swift-AI

**Description**: The Swift machine learning library with neural networks, ML algorithms.

**Tech Stack**:
- Swift
- Neural Networks
- ML algorithms
- Classic ML implementations

**Good For**:
- Understanding ML fundamentals
- Pure Swift implementations
- Educational contributions

**Difficulty**: Medium

---

### **6. CoreML in ARKit** ⭐ 1,704+ stars
**Repository**: https://github.com/hanleyweng/CoreML-in-ARKit

**Description**: Detect objects and display 3D labels in AR using CoreML. Template for ARKit + CoreML projects.

**Tech Stack**:
- Swift
- ARKit
- CoreML
- Computer Vision
- 3D rendering

**Good For**:
- AR + AI integration
- Object detection in AR
- Computer vision applications

**Difficulty**: Medium-Hard

---

### **7. YOLO CoreML MPSNNGraph** ⭐ 946+ stars
**Repository**: https://github.com/hollance/YOLO-CoreML-MPSNNGraph

**Description**: Tiny YOLO for iOS using CoreML and Metal Performance Shaders Graph API.

**Tech Stack**:
- Swift
- CoreML
- YOLO object detection
- Metal Performance Shaders
- Real-time inference

**Good For**:
- Object detection
- Performance optimization
- Metal/GPU programming

**Difficulty**: Hard

---

### **8. NSFWDetector** ⭐ 1,647+ stars
**Repository**: https://github.com/lovoo/NSFWDetector

**Description**: Content safety detector using CoreML for image classification.

**Tech Stack**:
- Swift
- CoreML
- Image classification
- Content moderation

**Good For**:
- Classification models
- Content safety
- Production ML applications

**Difficulty**: Easy-Medium

---

## 📝 Types of Contributions

### **Easy (Start Here!)**
- 📚 **Documentation improvements**
  - Fix typos
  - Add usage examples
  - Improve README
  - Add code comments

- 🐛 **Bug reports**
  - Test on different devices
  - Report issues with steps to reproduce
  - Validate existing bugs

### **Medium**
- 🧪 **Tests**
  - Add unit tests
  - Add UI tests
  - Improve test coverage

- 🐛 **Bug fixes**
  - Fix reported issues
  - Handle edge cases
  - Improve error handling

- 📖 **Examples**
  - Create demo apps
  - Add tutorials
  - Build sample projects

### **Advanced**
- ✨ **Features**
  - Implement requested features
  - Add new model support
  - Optimize performance

- 🏗️ **Architecture**
  - Refactor code
  - Improve APIs
  - Add new capabilities

---

## 🚀 How to Start Contributing

### **Step 1: Choose a Project**
Pick one from the list above based on your interest and skill level.

### **Step 2: Set Up**
```bash
# Fork the repository on GitHub
# Clone your fork
git clone https://github.com/YOUR_USERNAME/PROJECT_NAME.git
cd PROJECT_NAME

# Add upstream remote
git remote add upstream https://github.com/ORIGINAL_OWNER/PROJECT_NAME.git
```

### **Step 3: Find an Issue**
- Look for `good first issue` labels
- Check open issues list
- Ask maintainers what needs help

### **Step 4: Make Your Contribution**
```bash
# Create a branch
git checkout -b feature/your-feature-name

# Make your changes
# Test thoroughly

# Commit
git add .
git commit -m "Add feature: description"

# Push
git push origin feature/your-feature-name
```

### **Step 5: Create Pull Request**
- Go to your fork on GitHub
- Click "New Pull Request"
- Describe your changes clearly
- Link to related issues
- Wait for review

---

## 💡 Contribution Tips

### **Before You Start:**
- ✅ Read the project's CONTRIBUTING.md
- ✅ Check existing issues and PRs
- ✅ Set up the project locally and make sure it runs
- ✅ Start small - documentation is a great first contribution

### **While Contributing:**
- ✅ Follow the project's code style
- ✅ Write clear commit messages
- ✅ Add tests for new features
- ✅ Update documentation
- ✅ Test on real devices if possible

### **Best Practices:**
- 🎯 One feature/fix per PR
- 📝 Clear, descriptive PR titles
- 🧪 Include tests
- 📚 Update docs
- 💬 Respond to review comments promptly
- ✨ Be respectful and patient

---

## 🏆 Benefits of Contributing

### **Learning:**
- 📱 Advanced iOS development
- 🤖 CoreML and on-device ML
- 🏗️ Large codebase navigation
- 👥 Collaboration skills
- 📖 Best practices from experienced developers

### **Career:**
- 💼 Portfolio building
- 🌟 Open source experience for resume
- 🤝 Networking with iOS/ML community
- 🎓 Learning from code reviews
- 🏅 GitHub achievements (Pull Shark, Open Sourcerer)

### **Community:**
- 🌍 Give back to open source
- 💪 Help other developers
- 🎉 See your code used by thousands
- 🤗 Build reputation in iOS community

---

## 🎯 Recommended Path for Beginners

1. **Start**: Documentation fix in **CoreMLHelpers** or **NSFWDetector**
2. **Next**: Bug fix in **FluidAudio**
3. **Then**: Feature in **Swift CoreML Diffusers**
4. **Advanced**: Contribute to **MochiDiffusion** or **YOLO CoreML**

---

## 📚 Learning Resources

### **CoreML:**
- [Apple CoreML Documentation](https://developer.apple.com/documentation/coreml)
- [Creating an ML Model for iOS](https://developer.apple.com/documentation/coreml/creating_an_ml_model_for_ios)

### **iOS ML:**
- [Awesome CoreML Models](https://github.com/likedan/Awesome-CoreML-Models)
- [iOS Machine Learning](https://github.com/alexsosn/iOS_ML)

### **Contributing:**
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [First Timers Only](https://www.firsttimersonly.com/)

---

## 🔗 Quick Links

- [Good First Issues in Swift](https://goodfirstissue.dev/language/swift)
- [GitHub Swift Topics](https://github.com/topics/swift)
- [CoreML Topic](https://github.com/topics/coreml)
- [Machine Learning in Swift](https://github.com/topics/machine-learning?l=swift)

---

## 📊 Track Your Progress

- [ ] First documentation contribution
- [ ] First bug fix
- [ ] First feature implementation
- [ ] 5 merged PRs (Pull Shark Silver progress)
- [ ] Contributed to 2+ projects (Open Sourcerer)
- [ ] 10 merged PRs
- [ ] 16 merged PRs (Pull Shark Silver!)

---

**Happy Contributing!** 🚀

Made with ❤️ for iOS + AI developers

---

**Last Updated**: February 2026
