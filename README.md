Forked [ash11sh/remove-glass](https://github.com/ash11sh/remove-glass). Demo it in Windows 10.

Usage :

- Install requirements :

  ```
    pip install --upgrade -r requirements.txt
    pip install scikit-image
    pip install --extra-index-url https://google-coral.github.io/py-repo/ tflite_runtime
  ```


- Run the web-app locally using command : &nbsp;`python app/server.py serve`

  ```
    cd ash11sh_remove-glass
    python app/server.py serve
  ```
   if execute success, the logs,

   ```
    (ash11sh--remove-glass) λ python app/server.py serve
    INFO:     Started server process [12180]
    INFO:     Waiting for application startup.
    INFO:     Application startup complete.
    INFO:     Uvicorn running on http://0.0.0.0:5001 (Press CTRL+C to quit)
   ```

- Open Browser page : &nbsp;`localhost:5001`

   <img src="" width="50%" height="50%">