# FeedStat-Analyzer
FeedStat Analyzer is a **Python-based toolkit** for parsing, processing, and analyzing feed view logs.  
It demonstrates practical **data engineering patterns** using real log datasets, with a focus on **reproducibility, modular design, and professional development workflows**.  
The project uses **Jupyter Notebooks** for interactive exploration and result sharing.  

<br><br>

## Key Python Concepts Demonstrated
• **File I/O with Context Managers** – Safe and efficient reading/writing of data using `with open(...)`.  
• **Data Serialization** – Storing structured data with `json` and `csv` modules.  
• **Iterators & Generators** – Processing log lines lazily to reduce memory usage for large datasets.  
• **String Manipulation** – Parsing timestamped log lines with methods like `split()` and `strip()`.  
• **Error Handling** – Robust parsing with `try/except` blocks for malformed or incomplete data.  
• **Notebook-Driven Development** – Organizing analysis in **Jupyter Notebooks** for reproducibility and collaboration.  

<br><br>

## Notable Tools & Libraries
• **JupyterLab** – Interactive, notebook-based development.  
• **IPython** – Enhanced interactive Python shell within notebooks.  
• **NumPy** – Numerical operations for aggregated log metrics.  
• **Pandas** – DataFrame-based log processing and analysis.  
• **Pygments** – Syntax highlighting in rich-text outputs.  

<br><br>

## Project Structure


## Project Structure 
```
src/
    .gitkeep
    .gitignore
    data/
        feed-views.log
        feed-views-semicolon.log
    ex00/
        load_and_save.ipynb
    ex01/
        basic_operations.ipynb
    ex02/
        auto.json
        preprocessing.ipynb
        .ipynb_checkpoints/
            preprocessing-checkpoint.ipynb
        data/
            auto.csv
            .ipynb_checkpoints/
                auto-checkpoint.csv
    ex03/
        selects_n_aggs.ipynb
        .ipynb_checkpoints/
            selects_n_aggs-checkpoint.ipynb
    ex04/
        enrichment.ipynb
        fines.csv
        owners.csv
        .ipynb_checkpoints/
            enrichment-checkpoint.ipynb
    ex05/
        optimizations.ipynb
        .ipynb_checkpoints/
            optimizations-checkpoint.ipynb
```
