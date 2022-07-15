---
documentclass: scrartcl
linkcolor: blue
urlcolor: blue
toccolor: blue
geometry: margin=1in
---

\pagebreak

# Introduction

The FluCoMa Toolkit is not limited to the actual code objects that use the "Fluid" prefix. FluCoMa is also a collection of learning resources, code examples, commissioned artworks, musicological articles, interviews, podcasts, a philosophy about interface design for creative coding, a conversation about the future of computer music, a curriculum of machine listening and machine learning topics, a community of users around the world, and more. The materials included here extend this ecosystem to encompass resources for pedagogues that might be used to teach FluCoMa in various settings. While some of the ideas and resources presented below are FluCoMa-specific, many of them are toolkit-agnostic and we hope that they can be used by anyone looking to teach machine listening and machine learning for creative music making.

The extent of the FluCoMa ecosystem supports our belief that "providing the tools" is not enough to achieve FluCoMa's mission: _enable techno-fluent musicians to use machine listening and machine learning in their creative practices_. To truly enable these artists we also must provide the motivation, inspiration, and knowledge, all in a way that is learnable for our main user base: computer musicians. Topics in machine listening, machine learning, computational thinking, and data science are often not included in the training of electronic musicians and therefore our task is to build bridges of understanding from the knowledge of computer music training to a degree of fluency with these topics that enables creative music making. 

## Methodology

The learning materials included have been created through participatory, iterative, and interactive design. The first draft of learning materials were developed based on feedback from the [composers commissioned](https://www.flucoma.org/commissions/) to create music with early versions of the toolkit. Their feedback on what was confusing about the initial versions of the tools, resources, examples, etc. led to a second draft of learning materials which were then used in over thirty workshops around the world with computer musicians from various backgrounds. The feedback from these workshop participants further refined the learning materials and have led to the broad ecosystem of learning resources now found as part of the FluCoMa Toolkit.

## Tiered Learning Resources

Because different learners will desire different degrees of fluency with these topics, we have tried to tier the learning resources accordingly. The most proximal resources (such as [help files](#creative-coding-environment-materials)) provide a working understanding of what an algorithm does alongside a musical example of how it might be used. Additional resources (such as the [internet resources](#web-reference)) provide a deeper understanding that might satisfy one's curiosity and/or build an intuition of what is happening "under the hood", both of which can enable a more informed manipulation of the tools. When appropriate, we also link to the white paper that describes the algorithm from an engineering perspective, should the learner wish to understand with that amount of technical detail. 

In some cases the path of pursuing additional resources is more extensive and less linear. This is especially true for the more complex tools in FluCoMa, such as with the neural network objects which have multiple web pages dedicated to them with varying degrees of technical information, any one of which might come after an initial introduction, but when taken all together encompass the degree of fluency we suggest for our learners and users. Learners who are eager to jump to manipulating the many neural network parameters might jump to [MLP Parameters](https://learn.flucoma.org/learn/mlp-parameters/), while a user who needs a little more time absorbing how a neural network works might opt for [MLP Training](https://learn.flucoma.org/learn/mlp-training/). (Also see [MLPRegressor](https://learn.flucoma.org/reference/mlpregressor/), [MLPClassifier](https://learn.flucoma.org/reference/mlpclassifier/), and [Training-Testing Split](https://learn.flucoma.org/learn/training-testing-split/))

Tiered learning resources allow the learner to pursue knowledge as far as they deem appropriate to feed their creative practice in a given moment. Providing the learner what the _need_ to know _when_ they _need_ to know it enables them to stay focused on a creative idea and not become overwhelmed by what could be a very large body of knowledge with a steep learning curve. This sensitivity to the relationship between creative pursuits and technical knowledge reflects earlier findings of FluCoMa outlined [here](http://www.ems-network.org/IMG/pdf_GREEN_TREMBLAY_ROMA_EMS18.pdf) as "‘Techno-Fluency’ and ‘Divergence’". By offering links to further resources the user knows where to keep learning if they need it at the moment or if in the future they decide to continue exploring.

## Music-Forward Resources

A unique aspect of the learning resources developed is the pair of beginning and destination points identified: our target learner is a creative musician with fluency in a creative coding environment (Max, SuperCollider, or Pure Data) and our goal is to provide them the knowledge needed to expand their creative practice with machine listening and machine learning algorithms. Keeping this in mind, we have always tried to keep our learning materials and examples musically oriented (as can be seen below). We aim to have the help files and example code make sound in a creative way. When possible we always offer test files and thought experiments that include materials familiar and relevant to our learner such as instrument samples, drum loops, synthesizer settings, measures of pitch and loudness, etc. We hope this not only explains an object and its interface, but also provides some copy-and-paste code to get started quickly, and generally gets the creative juices flowing while a user is engaging in the learning process.

## Active Learning

Bringing their own corpus, datasets, synthesizers
Using creativity as part of the assignments
Cross-environment peer learning
Problem Solving 

# Ecosystem of Learning Materials

## Creative Coding Environment Materials

Each creative coding environment (CCE) supported by FluCoMa (Max, SuperCollider, and Pure Data) has a native system for offering reference materials. In Max and Pure Data a "help file" provides annotated examples, while a "reference" offers additional description and detail about parameters. In SuperCollider all of this information is contained in one "help file" document. Despite this difference in interface, we have strived to keep the CCE-based FluCoMa materials similar across all three environments. This is enabled, in part, by the [shared documents used to render the reference materials](https://github.com/flucoma/flucoma-docs) for all three CCEs. 

The FluCoMa materials provided natively in the CCE is often the learner's first engagement with our supporting materials. Therefore, the information provided is intended to provide the learner/user a working understanding of what an object does, how it might be used musically through a sound-making example, and if appropriate, how it interfaces with other FluCoMa objects. This information will hopefully provide a learner some motivation for exploring an object and the amount of knowledge necessary to do so. Each resource in the CCE contains a link to the corresponding [web reference](#web-reference) if the learner wishes to pursue a deeper understanding of the object.

The example code provided in the CCEs has been created to be as-similar-as is possible and idiomatic across the three coding environments. One goal of this is to enable cross-environment communication and knowledge sharing. Users in one environment may be able to describe or explain an example to users in a different coding environment. It is also possible that this allows referencing help files and example code to a classroom containing a diversity of coding environment users. Lastly, this keeps all three CCEs on an equal status, preventing any potential inference of CCE preference within the FluCoMa Toolkit.

## Web Reference

Every object in FluCoMa (except CCE-specific objects) has a web reference found at [learn.flucoma.org](https://learn.flucoma.org). Because the materials that appear natively in the CCEs link to the web, the web references are considered to be a secondary resource. The goal of the web references are to offer more detailed descriptions of how an algorithm is working "under the hood". This may be useful for satisfying curious learners, or it may build a better intuition of what a particular FluCoMa object might be used for musically. In either case, it should lead to a more informed, and therefore potentially more advanced, use of the object.

Many of the web references have interactive explanations that allow a learner to "use" the algorithm in the browser. We have found that these are very useful for explanations in the course of teaching. For example, when creating a KDTree for the first time during a code-along class, using the [interactive page](https://learn.flucoma.org/reference/kdtree/) helps give learners a visual sense of what is happening (especially if the KDTree is about to be used with the plotter). The [MFCC reference](https://learn.flucoma.org/reference/mfcc/) has an [interactive explanation](https://learn.flucoma.org/reference/mfcc/explain/) that invites a learner (or a teacher as a demonstration) to step through a series of interactions that build intuition about MFCCs.

We imagine the web references to be used as solo-learning resources, in parallel with class assignments, teaching demonstrations, and/or useful reminders.

## Learn Articles

FluCoMa's learning website ([learn.flucoma.org](https://learn.flucoma.org)) also contains many articles about topics that may not fit in a single web reference page. These articles are viewed as a tertiary step in a learners path and are likely to be encountered after the CCE materials and web reference.

There are a few varieties of articles found in this category:

* explainers specific to a single FluCoMa object but offer a depth of knowledge about the internal algorithms that would be outside the scope of a web reference page, such as [Audio Decomposition using BufNMF](https://learn.flucoma.org/learn/bufnmf/).
* knowledge about data science that is useful for using many of the FluCoMa objects, such as [Distribution and Histograms](https://learn.flucoma.org/learn/distribution/) and [Why Scale? Distance as Similarity](https://learn.flucoma.org/learn/why-scale/)
* common workflows using the toolkit, such as [Batch Processing with FluCoMa](https://learn.flucoma.org/learn/batch-processing/)

These articles are not necessarily designed to be consumed in series as part of a sequence of learning (although some could be used this way). Instead, each article is made to be approached by a learner (or guided by a teacher) at a particular point in the learning process and revisited as necessary. The idea for many of these articles arose in direct response to questions asked by workshop participants and therefore are designed to answer or provide context to common questions asked by learners. When designing a curriculum (such as the one [below](#suggested-semester-long-syllabus)), many of these articles would support student learning for different topics in the course.

## Explore Articles

In addition to the web reference and learn articles, the website has many [additional materials](https://learn.flucoma.org/explore/) surrounding artistic uses of the toolkit. These include example artworks, interviews with creative coders, and musicological articles that offer in-depth analysis and example patches of music made with FluCoMa. All of these can be used as context, examples, and inspiration for learners. 

## Discourse

The international community of FluCoMa users primarily communicates through the [Discourse](https://discourse.flucoma.org/) online discussion forum. Any learner (or user) of FluCoMa should be a member of the Discourse as it is an excellent place to converse with like-minded artists. Learners may find the search functionality very useful to see if others have already asked and answered a question they have. The community is very positive and supportive, so it is a safe place to ask all kinds of questions. In addition to the thread for _Usage Questions_, there are also threads for _Code Sharing_, _Learning Resources_, and _Interesting Links_, making it another place for learners to browse for examples, inspiration, and knowledge. 

## Inter-connectivity of Resources

As described above, the FluCoMa learning resources are generally tiered to offer learners the degree of detail needed at a given moment to pursue a creative idea. One way in which our tiered approach is executed is cross referencing the different learning resources. The help files in each creative coding environment (CCE) link to their respective web reference, from which a learner can be linked to many more resources. The web reference, learn articles, and explore articles all cross-link with each other so that a learner reading a web reference might discover an explore article about a musician's use of an object, and from there discover a learn article that might help them pursue the creative use they just learned about. All of this cross-linking supports our view that the learning process should allow for non-linearities. Different learners will need different degrees of technical specificity, inspiration, and modes of engagement at different times. We hope that setting someone "loose" on the website will enable them to find uses of FluCoMa that are meaningful to them as well as the knowledge needed to support them.

# "101" Tutorials

After teaching numerous workshops we have identified a few class plans that work well to get new learners excited and making sound as well as laying a foundation of facility with FluCoMa to support further activities and/or self-guided learning. A few of these lesson plans are described briefly below.

## MLP Regressor & Classifier

[_Watch a Video Tutorial of this Lesson Plan_](https://www.youtube.com/watch?v=XfNZzQPdPG0)

Often the first activity we engage with students is to build a neural network that performs regression to control a synthesizer. This gets learners making sound quickly and uses part of the toolkit that is often quite exciting for newcomers to machine learning to engage with. This activity takes any where from 40-90 minutes depending on the class of learners. Here is a brief outline of the lesson plan:

1. Share a [real world example](https://learn.flucoma.org/examples/teaching-material/regressor-example.pdf) (including watching a [performance excerpt](https://vimeo.com/565771489)) of why someone might want to use a system like this.
2. Using a [slides presentation](https://learn.flucoma.org/examples/teaching-material/regressor-process.pdf) step through how we will be collecting training data and training the neural network, including how some intuition about how the training process works.
3. Open up the CCE of choice and demonstrate a completed version of the instrument we're about to code.
4. Code the instrument together, as a code-along, starting from a "starter patch" that has a few key items already in place:
    - a synthesizer to control
    - a 2D control space to use as input to the neural network
    - a MLPRegressor object with many arguments already specified
5. Let the learners play with the instrument (and augment it in their own way).

The starter patch is important here so that we don't spend too much time doing CCE-specific boiler plate code but instead get right into using FluCoMa. It also ensures that learners have a synthesizer to make sound with right away when the code-along is complete. Because there are many arguments to the MLPRegressor object and each of them can require a fair amount of explanation to use well--and in coordination with each other--we've chosen to provide the arguments to the MLPRegressor in the starter patch. During the lesson we tell the learners that these arguments can be explored further in a future lesson and/or on our [learn article](https://learn.flucoma.org/learn/mlp-parameters/).

The extensions of this activity are to:

1. Practice training the neural network.
    - clearing the neural network and retraining
    - training the neural network to a less-low loss value to see if a less-fit model is more (or less, or differently) musically expressive
    - delete the input data and choose new input points to pair with the synthesis parameters already chosen
    - delete all the data and create a whole new training
2. Attach a different sound-making algorithm to the output of the neural network
    - granular synthesis / sample playback
    - frequency modulation
    - VST
    - we have often encouraged learners to bring a sound-making algorithm of their design to the workshop to connect as a next step to this activity
3. Attach a different type of controller to the input of the neural network. This might be something like:
    - multiple parameters on TouchOSC
    - MIDI controller
    - leap motion
    - wearable device
    - pixel information from a camera (perhaps using Jitter in Max)

Not only does this activity quickly provide learners with a machine learning instrument that is very extensible, it also introduces some of the key elements of FluCoMa:

1. DataSets
2. Buffer interfacing
    - fluid.buf2list~ and fluid.list2buf~ for Max
    - FluidBufToKr and FluidKrToBuf for SuperCollider
3. Using artist-created DataSets
4. Aesthetic evaluation of results
5. Iterative trial-and-error workflows with machine learning algorithms

### Classifier Extension

After completing the MLPRegressor activity, one common extension is to do an activity with the MLPClassifier. Depending on the group of learners and how much time we had, sometimes this would only include opening up the classifier demonstration file and doing a quick training and testing, along the way relating it to what was just done with the MLPRegressor activity. If time allowed and there is interest it could involve a similar process:

1. Share a [real world example](https://learn.flucoma.org/examples/teaching-material/classifier-example.pdf) (including watching a performance excerpt, this one has a [before]() and [after]()) of why someone might want to use a system like this.
2. Using a [slides presentation](https://learn.flucoma.org/examples/teaching-material/classifier-process.pdf) step through how we will be collecting training data and training the neural network, including how some intuition about how the training process works.
3. Open up the CCE of choice and demonstrate a completed version of the instrument we're about to code.
4. Code the instrument together, as a code-along, starting from a "starter patch" that has a few key items already in place:
    - a synthesizer to control
    - a 2D control space to use as input to the neural network
    - a MLPRegressor object with many arguments already specified
5. Let the learners play with the instrument (and augment it in their own way).

## 2D Sound Browser

## Introduction to NMF

# Common Learning Challenges & Strategies

## New Ways of Using Buffers

Buffer interface  
Time series of audio  
Time series of not audio  
Arrays (the idea that it would be not a time series)  
Reasoning for why buffers are used  
Specific complaints from users  
Strategies for responding to these challenges  
Changes in how buffer interfaces work in CCEs evolving  

## Advanced Neural Network Tutorials

## Stateful Objects

Stateful objects  
Added names to objects (max & pd) (sc already has variable names)

## Threading

### Max

### SC

## Dealing with Time

## Navigating Human & Machine Assumptions

Know Your Data  
Nearest Neighbor
Scaling & Distances
Stats  
Histograms
Clustering as an example  

## De-Myth-ifying Machine Learning

# Multi-Day Workshops

# Suggested Semester-Long Syllabus

# Relevance to Contemporary Society

# More Information