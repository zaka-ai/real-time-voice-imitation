<div align="center">

# Real-time Voice Cloning

[![Colab](https://img.shields.io/badge/Colab-Interface-blue?style=for-the-badge&logo=googlecolab)](https://drive.google.com/file/d/1ac2mTL1rRbYAZy8lOEviNW108jToKyGL/view?usp=sharing)
</div>

### Overview
This project features an intuitive interface that harnesses the power of two advanced models: the RVC (Real-Time Voice Cloning) model and the Coqui TTS v2 model. By integrating these models, the system enables seamless voice imitation and high-quality text-to-speech capabilities. The interface also incorporates W-Okada software, enhancing performance and user experience. Notably, this system allows for real-time inference, making it ideal for applications that require immediate voice synthesis and cloning.

#### Features
- Support for RVC V2 Model ✅
- Integration with W-Okada software, allowing you to download your own RVC models ✅
- Downloadable converted audio files ✅
- Microphone support ✅
- Compatibility with Coqui TTS ✅
- Real-time performance ✅

### How to Run the Interface

1. Download the [Hubert Model](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/hubert_base.pt).

2. To utilize RMVPE pitch extraction, download this [rmvpe.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/rmvpe.pt).
   
3. Upload these files to your Google Drive, ensuring you update the paths in the Colab.

4. Upload your RVC models (.pth and .index files) to your Google Drive, making sure to adjust the paths in Colab accordingly.

5. Upload your Coqui TTS model files (.pth, vocab.json, config.json) to your Google Drive, modifying the paths as needed.

6. Run the Colab and launch the Gradio link.

### Colabs Used <br />

For RVC training:
[![Colab](https://img.shields.io/badge/Colab-RVCTraining-blue?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/drive/1o7qkdxe4vfeoqf8d166RSzfvLwkl5YQ-?usp=sharing)

For Coqui TTS training:
[![Colab](https://img.shields.io/badge/Colab-coquiXTTSTraining-blue?style=for-the-badge&logo=googlecolab)](https://drive.google.com/file/d/1ofUzeZYO7AwsEG2tt8g34gco9XnuFdbS/view?usp=sharing)

### Technical Blog <br />
[![Blog](https://img.shields.io/badge/Blog-green?style=for-the-badge&logo=googlecolab)](https://docs.google.com/document/d/1tBTDE46vb-kL2-4iJqQGDfg1ua-kAUrvk5hc4eaNkIY/edit?usp=sharing)
</div>
