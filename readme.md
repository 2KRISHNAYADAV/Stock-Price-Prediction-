# StockMario AI - Technical Architecture & ML Pipeline

## Machine Learning Stack & Engineering

This project implements a state-of-the-art hybrid forecasting engine that merges qualitative deep reasoning with quantitative time-series modeling. Below is a professional technical breakdown suitable for high-level engineering resumes.

### Professional Summary for Resume
"Architected and deployed a multi-stage financial forecasting pipeline utilizing a **High-Parameter Transformer Architecture** with **Advanced Reasoning Heuristics** for multi-source sentiment extraction and complex pattern recognition. Engineered a hybrid ensemble combining **Long Short-Term Memory (LSTM)** networks for non-linear dependency capture and **ARIMA (Auto-Regressive Integrated Moving Average)** for statistical trend modeling. Integrated real-time data ingestion via **Google Search Grounding** to perform automated, high-fidelity market analysis and risk assessment."

### Core Technical Architecture:

1.  **Advanced Reasoning Transformer (The "Brain")**:
    *   **Architecture**: High-parameter Transformer model optimized for deep-chain reasoning and logical deduction.
    *   **Function**: Acts as the primary heuristic engine, processing unstructured news data and historical price vectors simultaneously.
    *   **Capabilities**: Performs **Zero-Shot Sentiment Extraction** and **Multi-Step Trend Reasoning**, simulating the decision-making process of a senior market analyst.

2.  **Hybrid Time-Series Ensemble**:
    *   **LSTM Component**: Implements gated recurrent units to identify long-term temporal dependencies and cyclical market behaviors.
    *   **ARIMA Component**: Provides a robust statistical baseline by modeling auto-regressive and moving average components to ensure forecast stability.
    *   **Ensemble Strategy**: Weights qualitative reasoning (Transformer) against quantitative trends (LSTM/ARIMA) to generate a unified 7-day price forecast with associated confidence intervals.

3.  **Feature Engineering & Indicator Pipeline**:
    *   **Technical Analysis**: Automated extraction of **RSI (Relative Strength Index)**, **MACD (Moving Average Convergence Divergence)**, and **SMA (Simple Moving Averages)** from raw price streams.
    *   **Sentiment Vectors**: Converts real-time news headlines into qualitative sentiment scores (Positive/Negative/Neutral) to adjust the model's bias.

4.  **Uncertainty Quantification**:
    *   Generates dynamic **Confidence Scores** and **Price Range Envelopes** (High/Low) based on model variance and market volatility indicators.

5.  **Real-Time Infrastructure**:
    *   Built with a high-frequency update loop to simulate live market ticks and continuous model re-evaluation.
    *   Utilizes **Google Search Grounding** for real-time external context, ensuring the model is aware of breaking news and market-moving events.
