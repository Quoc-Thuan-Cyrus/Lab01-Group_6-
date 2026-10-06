# UI

This folder is reserved for the user interface of the Smart Virtual Assistant.

The interface will be built later using Streamlit or Gradio in the practical session.

## Current status

This folder is intentionally left empty for Lab 1 and serves as a placeholder for the future UI implementation.

## Planned functionality

- display a chat interface for the assistant
- allow users to enter questions in the browser
- connect the UI to the backend logic in `src/assistant`

## Example setup for later

### Streamlit
```bash
pip install streamlit
streamlit run app.py
```

### Gradio
```bash
pip install gradio
python app.py
```

## Notes

For the current lab, the main logic is implemented in the Python backend and can be run with:
```bash
python -m assistant "where is the training office?"
```