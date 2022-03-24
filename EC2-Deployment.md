



> Some useful commands

```
  - cd etc/nginx/sites-enabled
  - sudo nano fastapi_config
  - **Update proxy address**
  - sudo nginx -t
  - sudo service nginx restart
  - tmux new -s sess_name
  - python -m uvicorn fastapi_app:app --reload
  -
  - tmux atach -t sess_name
 ```
 
 > FasiAPI + Uvicorn is fastest, and better than Flask:
 
  **Asynchonous requests: enables code to run separately from main application**
  - **async**, handler
  - **await**, before calling
