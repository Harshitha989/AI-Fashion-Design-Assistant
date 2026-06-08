# Week 2 Report – Text-to-Image Foundation

## Project

AI-Powered Fashion Design Assistant with Generative Models

## Objective

The objective of Week 2 was to set up a Stable Diffusion XL pipeline, perform prompt engineering experiments, evaluate generated images using CLIP similarity scores, and create reusable fashion prompt templates.

## Task 1: Stable Diffusion XL Setup

Stable Diffusion XL (SDXL) was successfully configured and executed using Google Colab with GPU support. The model was loaded using the Diffusers library and integrated with Hugging Face authentication.

Generated Fashion Designs:

* Blue Hoodie
* Black Jacket
* Denim Jacket
* Red Dress
* Red Summer Dress
* White Hoodie
* Violet Hoodie
* Navy Blue Suit
* Brown Saree
* Maroon Lehenga

## Task 2: Prompt Engineering Experiments

Different prompt styles were tested to study their effect on image quality and design generation.

### Basic Prompt Example

"A blue hoodie"

### Detailed Prompt Example

"A modern blue oversized hoodie, streetwear fashion, professional fashion photography, highly detailed fabric texture, studio lighting"

### Observation

Detailed prompts produced more realistic and visually appealing fashion designs compared to simple prompts.

## Task 3: CLIP Score Evaluation

Generated images were evaluated using the CLIP model to measure semantic similarity between text prompts and generated images.

### Results Summary

| Image            | CLIP Score |
| ---------------- | ---------- |
| Black Jacket     | 0.2721     |
| Blue Hoodie      | 0.3323     |
| Brown Saree      | 0.3311     |
| Denim Jacket     | 0.2434     |
| Maroon Lehenga   | 0.3425     |
| Navy Blue Suit   | 0.3150     |
| Red Dress        | 0.3364     |
| Red Summer Dress | 0.3092     |
| Violet Hoodie    | 0.3443     |
| White Hoodie     | 0.3169     |

### Observation

CLIP scores ranged between 0.24 and 0.34. Lower scores were observed when short prompts were used to evaluate images containing additional visual details such as models, lighting conditions, and fashion photography elements. Detailed prompts generally improved semantic alignment between text and image.

## Task 4: Prompt Template Library

Reusable fashion prompt templates were created for:

* Casual Wear
* Streetwear
* Luxury Fashion
* Formal Wear

These templates can be reused for future fashion image generation tasks.

## Conclusion

Week 2 successfully established a text-to-image generation workflow using Stable Diffusion XL. Prompt engineering techniques were explored, generated images were evaluated using CLIP similarity scores, and reusable prompt templates were created. The outcomes of this week provide a strong foundation for the upcoming ControlNet-based fashion design generation workflows in Week 3.
