# Scripts for CAE Turbulence Case Study

This folder contains the code needed to complete the CS3 case study:
**Reconstructing Turbulence Fields Using Convolutional Autoencoders.**

## Files

- `01_CAE_pipeline.ipynb`  
  Main notebook for the case study.  
  Students will:
  - Load the provided turbulence dataset  
  - Perform basic preprocessing  
  - Train a Convolutional Autoencoder (CAE)  
  - Generate reconstruction visuals (original vs. reconstructed fields)  
  - Answer short reflection questions about model performance  



## How to Use

1. Ensure you have the required Python packages installed (for example):  
   - `numpy`  
   - `matplotlib`  
   - `torch` (PyTorch)  

2. Place the dataset file into the `data/` folder as described in `data/README.md`.

3. Open the notebook:

   ```text
   scripts/01_CAE_pipeline.ipynb


---

### (Optional) Structure for `cae_case_study.ipynb`

When you build the notebook, a good section outline is:

- Title + brief description (Markdown)
- **Section 1:** Setup & imports  
- **Section 2:** Load dataset  
- **Section 3:** Preprocessing  
- **Section 4:** Define CAE model  
- **Section 5:** Train CAE  
- **Section 6:** Generate reconstruction visuals  
- **Section 7:** Short reflection prompts (Markdown cells with questions)

You can re-use your existing CAE code and just simplify it for 2nd-years.

---

Create `supplemental_materials/README.md` and paste this:

```markdown
# Supplemental Materials for CAE Turbulence Case Study

This folder contains readings that support the case study
**Reconstructing Turbulence Fields Using Convolutional Autoencoders.**

There are two main resources:

1. **Conceptual Explainer (Blog-Style)**  
   Recommended source:  
   *“An Introduction to Autoencoders for Beginners” – Analytics Vidhya* :contentReference[oaicite:0]{index=0}  

   This piece provides an accessible, beginner-friendly explanation of what autoencoders are, why they are used, and how they relate to tasks like dimensionality reduction and reconstruction. It is intended to help students build intuition before working with the CAE code.

2. **Technical Article (Deeper Dive)**  
   Recommended source:  
   *“An Introduction to Autoencoders” – Umberto Michelucci (arXiv, 2022)* :contentReference[oaicite:1]{index=1}  

   This article offers a more detailed description of autoencoders, including concepts such as reconstruction error, loss functions, and typical applications. It is suitable for students who want to understand the theory behind the model they are using.

## How Students Should Use These Materials

- **Before starting the notebook:**  
  Read the blog-style explainer to get a high-level understanding of autoencoders and their purpose.

- **While or after working through the notebook:**  
  Skim the technical article to connect the practical work in the case study with the underlying theory (e.g., reconstruction error and typical use cases).

In the physical manila folder for this case study, these two readings should be printed and placed on the right side, as specified in the CS3 rubric.


