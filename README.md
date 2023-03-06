# open-ai
Repo to document my learning curve while playing with the OpenAI API. <br>
Scripts / functions are stored in the [opai.conf](https://github.com/HeikoKramer/open-ai/blob/main/opai.conf) file. <br>
<br>
### overview of functions contained in the **opai.conf**:
## dalle
Bash function to generate images via OpenAI API via the command line. <br>
It'S the same service as via the DALL.E web interface, but faster, cheaper and without watermark. <br>
Their [image API](https://platform.openai.com/docs/api-reference/images) offers the possibility to specify:
* the prompt
* amount of images to be created (1-10)
* image size
* response format (weblink or base64)

The **dalle** function is asking for user input to specify the **prompt** and the **amount** of images. <br>
I've currently hard coded the highest possible image size (1024x1024) and I'm using the base64 format for the file generation. <br>
Example image: <br>
![OpenAi_image_API](/images/dalle_example.png)

