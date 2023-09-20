# AndroidDAMA
a smart privacy coding Android application powered by AI

## 🎇RoadMap
### Basic idea
- [ ] build a detection model that can detect all latent privacy content
- [ ] deploy the detection model on web (based on Gradio framework) to test model effects on internal user groups
- [ ] develop the Android application and release the first version to the public
- [ ] improve the app's func occording to the feedbacks
- [ ] embedding multimodal LLM in the APP so that users can use voice or text to command the system to automatically mask the private content
### A More Grand ideal
- [ ] directly using SAM (segment-anything-model, a visual general large model) to make it possible for user to mask anything they want and by any shape according to the shape of the thing needed to be masked
    - [ ] finetune the mobile-sam (a version that can be run on mobile phones) so that it can be easier to detect things that are latently needed to be masked, including avatars, names, times, dates, full lines of tex and small top icons
    - [ ] it's assumed that the app can deal with any type, any scene of images from any apps
## 🚗Work flow 
![Business Process Chart](img/业务流程图.png)
