Project presentation and submission
Mohammad Sadeghi posted on Mar 27, 2026 15:40
Overview

This semester project is a hands-on implementation project inspired by Andrej Karpathy's popular "Makemore" tutorial series (a 5-part YouTube playlist on building character-level language models using PyTorch). The goal is for student groups to fully reimplement the core concepts from scratch, demonstrating understanding of neural networks, training loops, and language modeling. 

The project emphasizes practical deep learning skills, such as:

    Data preparation (e.g., tokenization of text datasets).
    Building simple feedforward and recurrent neural networks (e.g., Bigram, MLP, RNN variants).
    Training and evaluation (loss functions, optimization, sampling generated text).
    Experimentation (hyperparameter tuning, model improvements).

By the end, each group will submit a working codebase that generates name-like text (or similar), along with a short report on insights and challenges.
Learning Objectives

    Reproduce a foundational deep learning pipeline from video tutorials.
    Collaborate on code in a group setting (using GitHub or similar for version control).
    Debug and iterate on models to achieve coherent text generation.
    Reflect on how architectural choices.

Scope and Deliverables

    Core Reimplementation: Follow all 5 videos closely:
        The spelled-out intro to language modeling: building makemore
        Building makemore Part 2: MLP
        Building makemore Part 3: Activations & Gradients, BatchNorm
        Building makemore Part 4: Becoming a Backprop Ninja
        Building makemore Part 5: Building a WaveNet

 

    Group Format: Work in teams of 3 students.
    Extensions (Optional for Bonus): Experiment with longer contexts, batching, or a simple transformer layer.
    Final Submission:
        GitHub repo with clean, documented code (Jupyter notebooks or Python scripts).
        Weight and biases in the format you think is the best
        Using mlflow for experiment
        A 2-3 page report/PDF: Summarize implementation, results (e.g., sample generated text, loss curves), and group contributions.
        Demo and presentation showing your model generating text.

Timeline and Milestones

Use this phased approach to stay on track. Adjust based on class schedule.

 
Milestone 	Description 	Due Date 	Responsible
Team Formation 			
Mid-Project Check-in 	Complete Videos 1-2or3. Implement MLP and backprop. Share progress in class (e.g., 5-min update). 	

Friday, April 10, 2026
	Full group
Final Presentation 	10 minutes final presentation and demo. 	

Friday, April 24, 2026
	Full group
Project Quiz  	20 MCQ from 5 videos 	

Friday, April 24, 2026
	Individual
Submission 	Upload repo and report 	

Friday, April 24, 2026 before class
	Full group
Resources

    Playlist: Andrej Karpathy's Makemore Series.
    Code Templates: Karpathy's GitHub repo for reference (but reimplement, don't copy-paste).
    Tools: PyTorch (install via pip install torch), Jupyter for experimentation. Use Google Colab if hardware-limited.

Evaluation Criteria (Total: 100 points)

    Code Quality (30 pts): Group
    midterm project update (10 pts): Group
    Report & Insights (20 pts): Group
    Presentation (20 pts): Individual 
    Project Quiz (20 pts): Individual / 20 MCQ from 5 videos

Tips for Success

    Start early—Videos 1-2 are quick, but latest videos debugging can be tricky.
    Common pitfalls: Shape mismatches in tensors, forgetting to set requires_grad=True, overfitting on tiny data.

If you have questions or need adjustments, let me know. Get those teams registered by tomorrow—excited to see your models in action!
