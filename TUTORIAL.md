1. Open Terminal, and type the following:
    - conda create -n streamlit-tutorial-env python=3.9 streamlit==1.24.0 pandas numpy scikit-learn plotly matplotlib seaborn scipy jupyter ipykernel xgboost lightgbm networkx folium
    - If the above code results in an error, delete 'networkx' and install it separately with pip
    - pip install streamit-folium
    - pip install pipreqs

2. Open a new 'cmd' terminal (not powershell). Look in the bottom right position of the VS Code
3. Type conda activate streamlit-tutorial-env
4. Di akhir, buat requirements.txt, dengan cara ke 'Streamlit Demo' dan type 'pipreqs'