# Lecture 1: Intro to Dashboards

## What is a dashboard?

- Information management tool that visually tracks, analyzes and displays key performance indicators (KPI) to monitor business, process, etc.
- Tools that provide up-to-date information about the state of the business
- Many definitions, so **need to precisely ask stakeholders what they want**

## Dashboard Technologies

- altair, plotly happens in **client side** (client-side interactive)
  - Front-end
  - Executes locally on client's browser
  - Portable, easy to share
  - Not as powerful and versatile as server-side interactive
- Want server-side interactive for more complex dashboards (e.g. with some ML model)
  - Back-end
  - Executes on server then sends to client
  - More powerful and versatile
  - Need to set up server, can be expensive and complex

### Dashboards in R

    - Shiny

### Dashboards in Python

    - **Plotly Dash**: Flexible, powerful, but complex
    - **Streamlit**: Good for simple dashboards
