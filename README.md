# Bot Setup and Execution Guide

## Environment Setup

1. Activate the conda environment:
    ```bash
    conda activate cat_env
    ```

## Running the Bot

2. Start the bot:
    ```bash
    cd core/core
    python -m cat.main &
    ```

3. Run the main script:
    ```bash
    cd Meowgram/src
    python main.py
    ```

## Stopping the Bot

4. To stop the bot, use `CTRL-C` on the bot

5. Bring the background process to the foreground:
    ```bash
    fg
    ```

6. Close the server by pressing `CTRL-C` again
