# jupyter-control-proxy : A Jupyter server proxy that enables Streamlit on top of JupyterLab/BinderHub
將論文轉成投影片 (PDF檔案轉成PPTX檔案)
jupyter-streamlit-proxy exposes and launches Streamlit via the relative URL
'streamlit', thereby enabling Streamlit-based web applications being launched
on top of an existing Binder infrastructure.  In addition it provides a button
within JupyterLab to launch and access the Streamlit web app via the GUI.

As the entry point for the webapp launch it expects a script at

`pip install git+https://github.com/arang129/jupyter_control_proxy.git`

`pip install --upgrade git+https://github.com/arang129/jupyter_control_proxy.git`

`pip uninstall jupyter_control_proxy`

which has the actual streamlit launch command inside, including the actual
file name of the web application.

A usage example, the Streamlit-based web application GlycoSHIELD, is available at   
https://gitlab.mpcdf.mpg.de/dioscuri-biophysics/glycoshield-md

The package is provided as-is, see 'LICENSE'.

This package was derived from   
https://jupyter-server-proxy.readthedocs.io/en/latest/
