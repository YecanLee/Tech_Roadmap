# Tech_Roadmap
A draft for personal tech roadmap


## Things to do in the coming 3 days
- [ ] Finish the implementation of the following models in our `fid-flaw` repo,  each customized model should be able to generate images based on two methods:   
1. no specific class-label flag is used as an input, the model will generate images for each class inside the ImageNet with `num_images_per_class` number of images.
2. a specific range of class labels are offered as part of the input, the model will generate images based on this specific label input.

Another thing should be done would be add a bash file to each method so the user can use it with only one line of command in terminal instead of several lines of code.

- [ ] Finish the score calculation of all experiments and update the repo, this needs to be done in a quick and smooth way, figure out two things:   
1. Is there anything really wrong with the Llama3.1 or the model just simply does not work with a specific method?
2. Is there any trick to accelerate the calculation even though it is already very fast?

- [ ] Finish the implementation of SAM2 for zero-shot instance segmentation, figure out if it is feasible to include a docker instruction so it will become more user-friendly. Try to understand if is possible to implement the new model into the `Groud-SAM` repo.

## Things to do in the coming one week
- [ ] learn `gradio` again, there must be an easy interface for the users to use the `Ceiling` model, no one wants to look at 1000 lines of commands in `README.md` even though it is very useful.
- [ ] learn `langchain` carefully, in case the job market becomes even worse, it would be easier to find a job in NLP filed compared to CV field.
- [ ] Finish the Howard video, rewrite the whole `DinoV2` model by using `CUDA` and try to benchemark it, this will serve as a basic practice.
- [ ] Must understand how onnx and TensorRT work and at least deploy a large model based on those methods.


## Some things to remember in case I forget about it
- [ ] Possible benchmark with both `bfloat16` and `float16` to test if there is any difference in the current pytorch version.
- [ ] Reimplement all the method in the `fid-flaw` repo by using `lightning`, this should be released as a package.
