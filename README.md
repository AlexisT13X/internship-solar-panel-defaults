----------- SOLAR PANEL ANOMALY CLASSIFICATION DETECTION -----------------

---- DESCRIPPTION ----

Deep learning project conducted during an internship at USTH (2025).
The goal is to classify thermal images of solar panels in order to identify different types of anomalies affecting their performance.
An advanced model was implemented and evaluated : Vim‑Tiny model adapted from an existing GitHub repository

The entire pipeline was developed in Python using PyTorch, and executed on Google Colab to take advantage of GPU acceleration.

---- HOW TO RUN ----

- Upload the dataset to your Google Drive.  
- Open the notebook in Google Colab.  
- Enable GPU execution in the runtime settings.
- Run the notebook cells in order to:
    -- load and preprocess the dataset,
    -- apply the defined transformations,
    -- train the selected model,
    -- evaluate its performance on the test set.  

---- RESULTS ----

- Accuracy ~27% on test set.  
- Best classified detection: MultiHotSpot & SingleByPassed.  
- Example: Image 2206 → Predicted MultiHotSpot (correct).  

---- REQUIREMENTS ----

- Python 3.x (core language)  
- PyTorch (model training)
- torchvision (image transforms)
- scikit-learn (metrics & evaluation)
- matplotlib (plots & visuals) 
- Google Colab (GPU runtime)
- Google Drive (dataset storage)


For any question : alexis_trezeux@reseau.eseo.fr
