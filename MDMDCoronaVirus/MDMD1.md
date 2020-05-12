# Analytic Thinking in the Time of Coronavirus
## Introduction
I think it is fair to say that there is more popular focus on analytic processes now than at any point in my lifetime. The coronavirus pandemic has led to a widespread interest in testing, data analysis, models and the decision-making procedures of governments around the world. 
While much of this focus is seemingly politically motivated (which leaders are doing well, which are doing badly, how does that confirm what we already thought about said leaders?), there is also a more general interest among people who want to understand what we know and how we know it.

It is also apparent that many journalists (though with some noted exceptions) lack experience of dealing with questions of this nature. 

What follows is my attempt to frame some of the difficulties that organisations and individuals face in using analytics effectively. It is not meant as a defence or an attack on any particular individual; rather, it tries to illustrate the complexity that we have to deal with. Sadly, it is not just a question of "applying the science" as I hope will become clear.

I am not going to precisely track the timeline and events or locations of the current pandemic. Instead, I am going to fictionalise a generic outbreak and think about how people respond. Where issues have arisen regarding the current outbreak that illustrate a point or warrant further discussion, then I will digress in order to do so.

It is important to note that I am not an epidemiologist, a medical doctor or a professional working in healthcare systems. As such, I may have framed some processes or professional practices incorrectly. Such errors are entirely mine, and I welcome correction, discussion and argument to improve this content.

## Definitions
### Measurement
Understanding how a real-world concept, phenomenon, or series of events can be detected, calibrated and logged is vital to the analytics process but is surprisingly often overlooked. 

Many analysts simply take data that they are given without questioning or properly understanding where it came from. This means that they may be ill-equipped to understand the implications of their model, to deal with problems, or to successfully take actions based on their analysis.

When thinking about measurement, we concern ourselves with accuracy, precision, bias, resolution, sensitivity, and the inevitable compromises that are made in taking measurements. We will think about what is and what is not included in any measurement and look at factors which may affect its quality.

### Data
Data is a collection of measurements or a record of discrete events and is the raw material that analysts work with. Understanding and knowing how to deal with data in aggregate form is a key skill. There is often too much of it, it is often of dubious quality and much of it won’t be directly relevant to the problem in hand. 
However, everything that we can learn through analytics is contained within the dataset. This isn’t to say that specific domain knowledge isn’t vital, but it can only aid understanding – it cannot add something which isn’t already present in the data, although it can alert you to missing or erroneous information. To this end we concern ourselves with how data is distributed and what it means, and how statistics can be used to adequately summarise a data set or reveal structure, and how it is cleaned and prepared for use.

### Models
Models are a simplified version of the real world. This necessarily means that there will be some factors which must be ignored while others take on greater importance. 

A model can range from a simple assumption or a rule-of-thumb to a complex statistical model, or set of interlinking models. 

When building or analysing models, it is necessary to understand the approximations and assumptions that have been made in the modelling process. The modeller should know under what circumstances assumptions become invalid. 
How do we go about building a model? What factors are critical, and which are optional? What interpretation can we put on modelling statistics to guide our choices? How do we identify hypotheses which can be supported by the evidence that we have available?

### Decisions
The entire analytics process must be focused on the problem that we are trying to solve. In that way, the rest of the process can be designed in a way that best supports that decision. 

Have we framed the problem accurately? Is the model suitable for this problem? Does it provide the necessary insights? How do we plan for various outcomes?
Often you are limited by the choices which you can make in any case. How do these constraints affect the modelling approach used? Why spend a fortune on gathering data and building sophisticated models if your "decision set" is too narrow to make use of it.
Ultimately, for the analytics process to make sense, the decision must affect the real-world process in a way that can be measured. If it can’t be measured, how do you know that your decision was correct? What was the point of the analytics exercise if it doesn’t lead to improvement?

## Phase 1

As stated above, all analytics processes would ideally start with considering the decision that is to be made. In this case, though, we have a problem - we don't even know that there is a decision to be made, let alone the correct option to take. It's one of those famous Rumsfeldian "Unknown unknowns". Something we don't even know about is attacking our systems and we've not yet caught on. So how exactly do we catch on?

Consider the earliest stage in the pandemic - a doctor becomes concerned by a new pattern of illness in his hospital.
Let's stop there and fit this into our framework as an example. 

### What's the model?
Our physician is troubled that something represents a shift from normal conditions, therefore he must have an idea what "normal" looks like. This is his model of his everyday reality. He would almost certainly find it hard to express it, or pass that model onto someone else, but it's there. Books like Malcolm Gladwell's "Blink" look at how people gain deep experience in a field that enable them to make decisions almost on "gut feel". Essentially that experience has given them a complex model with which to assess new situations. Our doctor has such a model and he thinks that something is off.

### Is there data?
The provocation was probably something like a larger than usual number of patients simultaneously becoming critically ill with similar unusual symptoms within a short period of time. One or two patients probably wouldn't have been sufficient to trigger an alarm. There must be a trend that is observable within the data that doesn't look good.

### What are we measuring?
It's important to realise that in this earliest stage, we are not measuring the impact of the virus because we don't know it exists. Our measurement tools are blunt - maybe simply a record of a death with certain symptoms preceding it. Even then, it requires people to make that "measurement" and people vary in their experience, in their observance, in their understanding and in their perseverance. Many early deaths may just have been dismissed as pneumonia with other co-morbidities. Old people die all the time and death certificates state "probable _" or "presumed _" or even just "undetermined". What this shows, however, is that an accumulation of blunt measurements can still convey important information.

### What should we do next?
The doctor has a whole range of choices that could be made at this point, for example:
- Delay until there is more data. Perhaps improve the measurements by, e.g., running further tests on patients with similar symptoms.
- Consult with colleagues, particularly in other nearby hospitals. Are they also seeing a worrying pattern? If they are, should it be escalated to the Deparment of Health or to the World Health Organisation?
- Ignore it and hope it goes away.

It's worth considering that the doctor will have many social and cultural factors that will play a part. For example, as related in Matthew Syed's book "Black Box", in studies of airline crashes, co-pilots from some more hierarchical cultures are more reluctant to challenge the decisions of the pilot, even when it could avert disaster.
In our situation, could it be that the doctor has asked another senior doctor for their opinion and been told not to worry? In medical training, doctors are told to look for horses, not zebras. A spike in air pollution might be the cause of more respiratory problems rather than a novel virus. A more senior doctor might know better... or they might be wrong. Such things can only be evaluated with hindsight. But it's probably true that there would be many more wrong pandemic alerts if junior doctors were expected to make the call. 

In some countries, there will be pressure from local or nation governments. Are they just afraid of being wrong and being ridiculed for it?

## Phase 2

### Measurement (System 2)
We have a new phenomenon to measure. Let's call it the "Is there an incipient pandemic?" measurement. In this case, our doctor is just a measurement tool, as prone to bias, inaccuracy, imprecision as any other. But we have a whole set of these tools, and we hope that the aggregation of their measurements will give us fair warning.

### Data, Models, Decisions (System 2)
The decision-makers at the WHO will receive notification that there could be a pandemic. They will have experience of previous cases, e.g., SARS, which provides context. If one doctor is known to report a pandemic every six months without ever having been right, they might be sceptical, as in "The boy who cried wolf". But they will gather other information and make requests for more data. Importantly, they may communicate that other countries and hospitals need to improve their measurement and will effectively suggest that doctors may have to adjust their expectations, e.g., change their models. In this way, doctors around the world may pay more than usual attention to patients with respiratory problems.

### Measurement, Data, Models, Decisions (System 1)
Back at the local level, the doctors have more choices to make:
- Should they isolate patients? Even without knowing for certain the cause of the illness, they know from experience (model) that this decision is likely to save lives at relatively low cost.
- What treatment should they use? There have been some concerns expressed that invasive ventilation can actually result in worse outcomes, but given a typical set of symptoms it still seems like the right decision. Critically, they know that as numbers of patients increase doctors will have less and less time to assess each patient as an individual. The model that a doctor normally forms in their head of a patient is going to become more general, with less room for nuance than they would like. THis is unfortunate but unavoidable.
- How do they record symptoms, interventions, outcomes in a way that will be as useful as possible in improving the model of the as-yet-unknown pathogen? It might be impossible to conduct all of the tests that they would like particularly under the conditions. If you could only have three tests, what might they be? If a test cannot be conducted immediately, will it still be valid? How do you balance resources to treat patients with the resources required to improve knowledge?






## A Matter of Testing

So we have established the need for testing, which comes under "measurement" in our framework. People are generally familiar with measurement of a physical property, where we use a ruler or a thermometer (both calibrated instruments) to estimate the property in question. Measuring a more abstract concept, e.g., voting intention, usually involves a survey or similar, but it is much harder to gauge the responses against a "true" value which remains unknown. The advertising guru David Oglivy once said that the problem with market research is that people don't think how they feel, they don't say what they think and they don't do what they say. All of these create uncertainty in the measurement.

Measuring something like "does this person have a certain virus" can be difficult. A trained person has to take a swab from a part of the body where the virus might be found, ensure it doesn't get contaminated, get it to a lab for testing. Even then, any test for the presence or otherwise will have issues with false positives and false negatives. To be clear, it is almost impossible to have a test which never returns either a false positive or negative. Even if the test is truly negative, the person being tested could acquire it in the immediate aftermath of being tested. All our measurement means is that the person in question did not have the virus at the moment they were tested.

An antibody test which can test whether the person in question has had and fought off the infection is clearly useful for a number of purposes, in particular:
- Checking if a person safe to return to proximity of vulnerable people
- Determining the percentage of people who have had the virus in the population

The ratio of false negatives to false positives takes on a different importance based on which purpose it is being used for. If it's for a population-level study, the accuracy of the test is less important because the new test data will primarily be used for calibrating models and estimating prevalence and the fatality rate. When calibrating this test, a 50/50 split between false positives and false negatives will still allow a robust estimate to be made.

If, on the other hand, you want to know if a person can visit a relative with pre-existing respiratory problems, false negatives are a much bigger problem than false positives. You really do not want to tell a person that is infectious that they are not. You might decide that this balance should be 1:20, i.e., you can tolerate 20 false positives for every false negative.

Yet again, though, incentives are different for different people. A researcher might want to test a person as part of investigating the population effects. The person themselves will want to know their result. 
A doctor treating a patient might want to know if their patient does indeed have COVID-19. But as Jason Leitch discussed with [Matt Forde][PolPartyJasonLeitch] there isn't currently a cure for COVID-19, making it less helpful. Treating the symptoms, coupled with knowledge about likely exposure, could be sufficient.
Even if a cure were to become available, there will be a question of side-effects. Imagine there was a treatment that was a guaranteed cure if the patient does have COVID-19 but will result in paralysis if the patient doesn't. In this case, the doctor would be far more afraid of false positives, particularly if there was another less-effective but less-dangerous alternative treatment. On the other hand, if the treatment is harmless if given to a patient without the virus, maybe you don't need a test at all - just give it to everyone as a matter of course. Unless it was very expensive per dose, etc., etc.



Some countries have taken to publishing daily estimates of R, the infection rate. For example, Germany [published][GermanyInfection] the following figures:
Friday 0.83
Saturday 1.1
Sunday 1.3
What possible reason could there be for the value of this parameter to vary so wildly (+57%) in the space of two days? The answer is almost certainly that someone is overfitting a model to randomly-varying, incomplete data and reporting an estimate without confidence intervals. It would be far more accurate (though less precise) to say that R is 1.05 ± 0.25. It would also vary within sub-populations - Tom Chivers wrote a good piece [here][ChiversRVal] about how different values in different sub-populations could mean that R increasing shows that interventions are working.




[GermanyInfection]:[https://www.thetimes.co.uk/article/coronavirus-germans-flout-rules-despite-pleas-to-obey-cnvm2gc62]

[ChiversRVal]:[https://unherd.com/2020/05/what-the-headline-covid-figures-dont-tell-you/]
[PolPartyJasonLeitch]:[https://soundcloud.com/thepoliticalparty/show-155-jason-leitch]