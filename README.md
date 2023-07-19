# AI Photo Object Removal 🐈

This is an application that allows you to remove objects from your photos using AI technology. It provides a user-friendly interface where you can draw over the parts of the image you want to remove, and the AI will automatically remove them.

## Setup

Start (Non Docker)

```
pip install -r requirements.txt
streamlit run app.py
```

Start (Docker)

```
docker-compose up
```

Then visit 127.0.0.1:<52xxx>

## Usage

1. Run the application:

   ```shell
   streamlit run app.py
   ```

2. Open the application in your web browser.

3. Choose an image by clicking on the "Choose image" button.

4. Adjust the brush size using the slider.

5. Draw over the parts of the image that you want to remove using the brush tool.

6. Click the "Submit" button to start the object removal process.

7. Wait for the AI to process the image. The output image will be displayed once the process is complete.

8. If you're not satisfied with the result, you can download the output image and upload it again to remove any artifacts.


## Acknowledgements

This application is based on the [ComicInpainting](https://github.com/petergro-hub/ComicInpainting) app code and the [LAMA](https://github.com/saic-mdal/lama) model. Special thanks to the authors of these projects for their contributions.

