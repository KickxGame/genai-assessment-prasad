# Generative AI Assessment – Prasad Uchil

## Overview

This repository contains my completed Generative AI assessment submissions, including generated outputs, reference assets, prompts, workflows, and process documentation.

The work demonstrates practical experience in AI-assisted image generation, image editing, visual consistency, compositing, and creative problem solving.

---

## Completed Assessments

### Assessment 1 – Image Editing & Background / Object Manipulation

#### Objective

Perform image editing operations using Generative AI techniques, including:

- Extending missing background areas
- Upscaling images to higher resolution
- Adding objects
- Removing objects
- Replacing backgrounds
- Maintaining character position, pose, proportions, and visual consistency

#### Approach

The source images were processed using Generative AI image-editing workflows with controlled prompting and image references.

Special attention was given to:

- Preserving the original subject
- Maintaining the original pose and position
- Matching perspective and lighting
- Controlling unwanted generated elements
- Maintaining a consistent visual style

#### Tools / Techniques

- FLUX-based image generation and editing
- Krea
- Image-to-image generation
- Reference-image conditioning
- Masked / controlled editing
- Prompt-based background replacement

#### Deliverables

The `Assessment 1` folder contains:

- Input/reference images
- Generated outputs
- Supporting workflow files where applicable

---

### Assessment 2 – Auralis Nova Product Advertising

#### Objective

Create a premium cinematic promotional key visual for the fictional consumer electronics brand:

**Auralis Nova – Wireless Headphones**

The visual direction focused on:

- Premium product presentation
- Strong product focus
- Modern technology aesthetic
- Cinematic lighting
- Sophisticated materials
- Immersive sound concept
- Negative space suitable for advertising copy

#### Creative Direction

A consistent master product image was first established and then used as the visual reference for additional advertising compositions.

The generated scenes explored:

- Hero product photography
- Floating headphone compositions
- Immersive sound-wave environments
- Premium lifestyle environments
- Macro product details
- Futuristic technology environments

#### Tools / Techniques

- FLUX-based image generation
- Krea
- Image reference conditioning
- Prompt-controlled composition
- Product consistency techniques
- Cinematic lighting and environment generation

#### Deliverables

The `Assessment 2` folder contains the generated promotional visuals and supporting assets.

---

### Assessment 3 – Generative AI Visual Task

#### Objective

The third assessment was completed using a Generative AI-based visual workflow according to the supplied assessment requirements.

#### Approach

The workflow focused on controlled image generation/editing while maintaining consistency between the provided references and the generated result.

Key considerations included:

- Subject consistency
- Composition
- Prompt control
- Reference-image usage
- Visual quality
- Artifact reduction
- Final output quality

#### Tools / Techniques

Generative AI image generation and editing workflows were used according to the requirements of the assessment.

#### Deliverables

The `Assessment 3` folder contains the relevant input/reference assets, generated outputs, and workflow files where applicable.

---

## Prompt Decomposition Strategy

The assessment requirements were broken down into smaller creative and technical components before generating the final outputs.

### 1. Understand the Source

Identify:

- Main subject
- Pose and position
- Camera angle
- Lighting
- Perspective
- Existing environment
- Important visual details

### 2. Define the Required Change

Separate the requested modification from elements that must remain unchanged.

For example:

- Background replacement → preserve subject
- Product replacement → preserve hand, pose and body
- Object removal → preserve surrounding environment
- Product advertising → establish product consistency first

### 3. Establish a Reference

Where required, a reference image was used to control:

- Character appearance
- Product design
- Clothing
- Environment
- Visual style

### 4. Control the Generation

Prompts were constructed with explicit instructions for:

- Subject preservation
- Position
- Composition
- Camera perspective
- Lighting
- Materials
- Environment
- Unwanted-object exclusion

### 5. Iterate

Generated results were reviewed and prompts were refined when issues occurred, such as:

- Subject movement
- Incorrect proportions
- Unwanted characters
- Incorrect background elements
- Lighting mismatch
- Product inconsistency
- Visual artifacts

### 6. Final Output

The strongest generated results were selected and prepared according to the assessment requirements.

---

## Tools Used

- Generative AI image generation and editing
- FLUX
- Krea
- ComfyUI where applicable
- Image reference workflows
- Prompt engineering
- Masked / controlled image editing

---

## Repository Structure

```text
genai-assessment-prasad/
│
├── Assessment 1/
│   ├── input/
│   ├── outputs/
│   └── workflow/
│
├── Assessment 2/
│   ├── input/
│   ├── outputs/
│   └── workflow/
│
├── Assessment 3/
│   ├── input/
│   ├── outputs/
│   └── workflow/
│
└── README.md
