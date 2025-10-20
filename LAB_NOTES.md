cat > LAB_NOTES.md << 'EOF'
🎛️ **Glowlock Sensory Engine (GSE)** 🌲✨  
*Prototype Pending · Stack: Python, SentenceTransformers, Streamlit, Matplotlib*

---

### Overview
This sprint from **Glowlock Labs** focused on prototyping a “sensory knowledge engine” for the Glowlock world. Each land—**Moss Merry Way**, **Jingle Hooves**, **Dusk Hallows**, and beyond—was encoded as a structured profile of taste, feel, color, sound, and smell. Using Python dictionaries and text embeddings, the system allows vibe-based search, art-prompt generation, and visualization of Glowlock’s realms.  

The goal: translate narrative worldbuilding into an **interactive ML artifact**.

---

### Goal
To prototype a machine learning–driven vibe dictionary that demonstrates how Glowlock Labs transforms creative lore into computational form—bridging sensory writing with embeddings, search, and visualization.

---

### Use Case
The engine serves as:

- A proof-of-concept for narrative-driven ML applications in creative tech  
- A demonstration of worldbuilding data pipelines (from sensory text → embeddings → recommendations)  
- A portfolio-ready artifact showcasing Glowlock Labs’ R&D process at the intersection of storytelling and machine learning  

---

### 🔧 Tech Stack
**Platform:** Python + Streamlit  

**Models/Tools:**
- Python Dictionary / JSON (for sensory land profiles)
- SentenceTransformers (for embeddings + vibe similarity search)
- NumPy + Scikit-learn (for clustering + cosine similarity)
- Matplotlib / UMAP (for 2D vibe map visualization)
- Streamlit (for interactive demo app with search, prompts, and maps)

---

### 🧪 Sprint Outcome
✅ Generated a 30-second snow-globe sequence with clear character expression  
✅ Achieved a storybook cinematic aesthetic consistent with Glowlock’s design language  
✅ Validated workflow for reference image → AI video → post-production polish  
✅ Delivered a prototype that positions **Glowlock Labs** as a pipeline-focused R&D studio  
❌ Exported final render for portfolio and lab archive (pending)  

EOF

mv README.md LAB_NOTES.md

cat > README.md

# Glowlock Sensory Engine (GSE) 🌲✨

An ML-driven **vibe dictionary** that turns Glowlock’s sensory lore  
(taste, feel, color, sound, smell) into embeddings for search,  
prompt-gen, and visualization.

## ✨ Features
- Encode Glowlock realms (e.g., *Moss Merry Way*, *Jingle Hoof*, *Dusk Hallows*) into embeddings  
- Free-text “describe a vibe” search (cosine similarity)  
- Prompt scaffolds for art/video generation  
- Streamlit demo app + Jupyter notebook workflow  

## 🚀 Quickstart
```bash
# clone
git clone https://github.com/raemchilds/Glowlock-Sensory-Engine.git
cd Glowlock-Sensory-Engine

# optional: create a venv
python3 -m venv venv && source venv/bin/activate

# install deps
pip3 install -r requirements.txt

jupyter lab  # or jupyter notebook

python3 -m streamlit run app.py
# then open http://localhost:8501

