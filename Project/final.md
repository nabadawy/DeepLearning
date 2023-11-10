# Project Final Delivery

For the final delivery of the project, you will need to finalize your work, make any necessary updates on your code/research, and present **all** the work done for the project, at this phase you're required to submit several deliverables and make a presentation that has the following requirements.

## The Presentation Requirements

**One important note about this presentation is that it has to cover all the project work, not only the work done after the second milestone.**

1. Original model from literature (in figures and diagrams only).
2. Proposed model architecture (in figures and diagrams only).
3. Final model architecture (in figures and diagrams only), explain if originally proposed parts weren't feasible which made you adopt new changes.
4. Graphs and plots that show your results.
5. A **live** demo of your working model. **(more details in the next points)**
6. Conclusion and future work (including lessons learned and interesting findings).
7. Each team member's contribution. You should state only the contribution to the technical work, so (designing the presentation or the poster, creating the website, writing the document for example, shouldn't be included). "We divided the work equally" is not accepted; have a clear division of work.

## Selected Presentations

1. [Floor Localization](assets/selected_final_presentations/localization.pdf)
2. [Text to Image](assets/selected_final_presentations/txt2img.pdf)
3. [Artistic Style Transfer For Videos](assets/selected_final_presentations/style_transfer.pdf)

## Deliverables

1. Presentation slides containing the requirements.
2. A recorded video of your presentation; this will give you a chance to rehearse and also be a point of reference for your work.
3. A recorded video of your model demo. (make it part of the presentation video)
4. A **live** presentation showing your work.
5. A **live** demo of your working model (part of the live presentation, if you think the demo will take too much time in the presentation, you can use a recorded video and explain what is happening in it to us in the live presentation).
6. Project Code.
7. A poster for your project (soft copy).
8. Project Website.

## The Project Code

The submitted code must satisfy the following requirements:

1. Code files in a Python Notebook/Jupyter Notebook **if possible**. But, in all ways, a full working code must be submitted.
2. A list of all dependencies and installation instructions to get the code fully working. (Readme.txt)
3. Data files, provide permanent links for huge datasets or upload the dataset directly to the submission form if tiny (less than 100 MB).
4. Your model weights, a permanent link if possible or upload it directly to the submission form if tiny (less than 1 GB).

## The Project Demo

It's required to deliver a live demo during your presentation, in this demo you are required to show us the model in practice, we need to see the model fed with clear examples and to see the actual output.

For example, in the case of image classification, we need to see the input image, the output class, and how confident the model is.

Don't show us the model accuracy or the training result, this part should show us a few examples of how this model could be used in **real-life practice**.

**Note**: You're also required to deliver a pre-recorded video of your model demo (as part of the presentation video), this video **should match exactly** the live demo you will make during your presentation to ensure fairness, any mismatch will be considered a fraud and penalized accordingly. In case your demo takes too long to run, you can use the recorded video in the live presentation (to speed up the process) but you must explain to us what is happening in the video.

## The Project Poster

The project poster is a pdf document for a one-page summary of your project. It has no specific requirements but the following guidelines should help:

1. Make sure to include the university logo, your names, and the project title.
2. Focus on graphs, figures, and diagrams. **Avoid having too much or too little text; balance between text and visuals**.
3. **Simple is safe**.

You can use any simple tools like Microsoft PowerPoint or Google Slides. You can start with free templates available online such as those found [here](https://www.genigraphics.com/templates) and [here](https://www.posterpresentations.com/free-poster-templates.html).

The following is a list of posters from previous terms, just follow the general style, nothing specific nor fancy is required.

1. [Movie Genre Classification](assets/selected_posters/movie_genre.pdf)
2. [Anomaly detection using AEs](assets/selected_posters/anomaly.pdf)
3. [Search for Similar Images](assets/selected_posters/similar_images.pdf)
4. [Floor Localization](assets/selected_posters/localization.pdf)
5. [Text to Image](assets/selected_posters/txt2img.pdf)
6. [Facial Expression Evaluation](assets/selected_posters/facial_expression.pdf)

## The Project Website

You are required to create a website page for your project, I will use this page to create a website to present all your projects in one place, for better understanding, you can have a look at the past project websites:

* [AUC - CS 4606: Practical Machine Deep Learning - Spring 2022](https://raw.githack.com/sherifmost/DeepLearning/master/Project/assets/auc_spring2022_website/home.html)

To create your website page, use the [website-template provided here](website-template/). The website-template has the following hierarchy:

```
website-template\
website-template\team-specific\
website-template\team-specific\index.html
website-template\team-specific\resources
website-template\vendor
```

Please download the whole website-template folder, make your changes then submit the team-specific folder with its exact folder hierarchy.  You're to make modifications **only** inside the **team-specific** folder, **never** make any changes out of it.

You will find inside the index.html a **whole template for a dummy project** I created. Just modify the content of the blocks to reflect your project details, please don't try to modify the styles and keep everything homogeneous. I've made an example of almost everything you might need inside the template, if you do this correctly, the website shouldn't take ten minutes to be done.

You can have a look at [the rendered webpage of the dummy project](https://raw.githack.com/KhaledElTahan/DeepLearning/master/Project/website-template/team-specific/index.html) for a better understanding.

**The provided sections in my dummy project are the requirements of the website**, please make any suitable updates you need based on your project specifics, for example, if you're using reinforcement learning then you may change the dataset section to be environment section.

This website template is based on [the bare bootstrap](https://startbootstrap.com/template/bare) website template.

## Notes

1. The presentation should be about all the course project, not the progress during final delivery only.
2. You are to continue your code/research work during this phase to finish all your proposed updates besides working on the other requirements.
3. You have to make the presentation using the submitted slides, a penalty is applied otherwise.
4. Your presentation will take only *nine minutes*, two of which are reserved for instructors, and your colleagues' questions/feedback. So, you need to make sure your presentation doesn't exceed *seven minutes*. Practice the presentation and make sure it fits within **7 minutes**.
5. **The recorded video of the presentation will be submitted days before your live presentation. Make sure not to get confused by this point.**
6. The recorded video of the presentation should not exceed **seven minutes** and should be at least **five minutes**.
7. The provided selected presentations, selected posters, and website might have been made under different requirements, just because any of them doesn't meet any of our requirements doesn't give you the ability to do the same.
8. For the live demo, we want to see a running application of your model with good illustrative examples or use cases. However, you decide which use case you will present to us and how to do it, no specific requirements or instructions for it.
