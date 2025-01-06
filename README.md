<p align="center">
  <img src="http://git.thewakesystems.com:8001/image/lajiao/chili.jpeg" width="400"/>
</p>


# Thewake ChiliPainter Software
ChiliPainter is an Al-supported painting software, special designed for AMD Ryzen CPU computation.
ChiliPainter is developed by AMD - Thewake Systems AI Application Joint Laboratory and sponsored by AMD.

# WakeDreamPainter Installation Instructions
After downloading the software from the Release Tag, you can directly install it. 

## Post-Installation Steps
After installation is complete, please download the required ONNX format models as follows:

1. **Basic Drawing Model**  
   You can download the basic drawing model from Hugging Face:  
   [TensorStack/LCM_Dreamshaper_v7-onnx](https://huggingface.co/TensorStack/LCM_Dreamshaper_v7-onnx)

2. **AI Filter Feature**  
   This feature requires the combination of two models:  
   - **Feature Extraction Model**: Download from [TensorStack/FeatureExtractor-onnx] (https://huggingface.co/TensorStack/FeatureExtractor-onnx)
   - **Processed Model via ControlNet**: Download from [ssslvky/lcm-hed-onnx](https://huggingface.co/ssslvky/lcm-hed-onnx)

# About This Project
This project is supported by AMD, developed based on [OnnxStack](https://github.com/TensorStack-AI/OnnxStack) and incorporates the following technologies:

1. **Stable Diffusion with C# and ONNX Runtime**  
   By Cassie Breviu ([@cassiebreviu](https://github.com/cassiebreviu))  
   Repository: [stablediffusion](https://github.com/cassiebreviu/stablediffusion)

2. **Diffusers**  
   By Hugging Face ([@huggingface](https://github.com/huggingface))  
   Repository: [diffusers](https://github.com/huggingface/diffusers)

3. **Onnx-Web**  
   By Sean Sube ([@ssube](https://github.com/ssube))  
   Repository: [onnx-web](https://github.com/ssube/onnx-web)

4. **Axodox-MachineLearning**  
   By Péter Major ([@axodox](https://github.com/axodox))  
   Repository: [axodox-machinelearning](https://github.com/axodox/axodox-machinelearning)

5. **ControlNet**  
   By Lvmin Zhang ([@lllyasviel](https://github.com/lllyasviel))  
   Repository: [ControlNet](https://github.com/lllyasviel/ControlNet)
