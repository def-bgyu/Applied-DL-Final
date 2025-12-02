# Text-to-Image Generation

A simple text-to-image generator that converts text prompts into AI-generated images.

## Model Used

**Stable Diffusion v1.5** (`runwayml/stable-diffusion-v1-5`)

## How to Run

1. Open the notebook (Google Colab)
2. Enable GPU: `Runtime` → `Change runtime type` → `T4 GPU` (if applicable)
3. Run all cells in order
4. Enter your text prompt in Cell 5 and run to generate an image

## Requirements

- Python 3.12
- PyTorch
- Diffusers library
- Google Colab (for GPU access)

## Example Usage

```python
user_prompt = "a beautiful sunset over mountains, digital art"
generated_image = generate_image(user_prompt)
```

## Author

Nidhi Sankhe
STAT 5350 - Final Project