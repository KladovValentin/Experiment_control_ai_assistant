# Experiment_control_ai_assistant
Initially a tool based on a fine-tuned multimodal large language model created to help in particle physics 'shifts' during the beam times

We take a trained multimodal LLN that can treat images, graphs, texts and histograms and then finetune it using reinforced learning to detect flaws in QA and DAQ.
First it can be trained on small simple dataset with good or bad images and then a feedback loop would be used before and during the beamtime to improve the accuracy and overal performance of the network.

List of desired features (not sorted):
* Text-to-speach with trained custom voice (should be special and memorable, easily recognisable, not just google voice).
*  Speach-to-text for human feedback: people don't have to write down descriptions why that is correct and this is not.
*  Able to pinpoint where something is wrong, why and, in an ideal world, propose a solution or the source (core) of the problem.
*  After the finetune should still be able to "chat": can be asked about the reasons in various ways, can react on human speach even without explicit call and learn from "raw" ordinary sentences.
*  Anime icon and picture.

Information:   
https://aclanthology.org/2023.findings-acl.27.pdf - fine tuning of multimodal pretrained models?   
https://huggingface.co/docs/transformers/v4.32.0/training - hugginfaces fine tuning guide   
https://arxiv.org/pdf/2308.04152.pdf - some other work about fine tuning   
https://github.com/zjr2000/Awesome-Multimodal-Chatbot - list of multimodal chatbots   
   
https://arxiv.org/pdf/2302.06692.pdf - reinforcement learining stuff   
https://kili-technology.com/large-language-models-llms/exploring-reinforcement-learning-from-human-feedback-rlhf-a-comprehensive-guide   


Problems:
Where to get pretrained LLM?
If we want to use very nice NN, how to fit it in the disc and VRAM? ChatGPT is 500 Gb...
How to train it initially? People will not do that on shifts. Have to run it on the GSI computer with an axcess to the data and train it by myself distantly? I'm not an expert...
