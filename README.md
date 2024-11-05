# Gravio Showcase

日本語が喋る方は[こちら](/README_JP.md)

This repository is where we collect and showcase both official and community Gravio snippets. You can find example [Actions](https://doc.gravio.com/manuals/gravio4/1/en/topic/edit-action) and [Triggers](https://doc.gravio.com/manuals/gravio4/1/en/topic/trigger-tab) here, as well as usage notes on each item.

For example, if you want to see how to use a specific component, say, the _SendHttpRequest_ component, you can search for actions with that component here.

Each Action comes annotated with the following notable fields:

|Field|Description|Values|
|-----|-----------|------|
|Components|List of [components](https://doc.gravio.com/manuals/gravio4/1/en/topic/action-components) this Action uses| {list of any valid component}|
|Payload|Whether this Action demonstrates usage of the [cv.Payload](https://doc.gravio.com/manuals/gravio4/1/en/topic/action-component-spec) object| {true,false}|
|Pre-Mappings|Whether this Action demonstrates usage of any [pre-mappings](https://doc.gravio.com/manuals/gravio4/1/en/topic/premappings-postmappings) fields| {true,false}|
|Post-Mappings|Whether this Action demonstrates usage of any [post-mappings](https://doc.gravio.com/manuals/gravio4/1/en/topic/premappings-postmappings) fields| {true,false}|
|Component Property|Whether this Action demonstrates usage of any [cp.](https://doc.gravio.com/manuals/gravio4/1/en/topic/available-variables-in-action#Component%20Property) fields| {true,false}|
|Component Value|Whether this Action demonstrates usage of any [cv.](https://doc.gravio.com/manuals/gravio4/1/en/topic/available-variables-in-action#Component%20Variable) fields| {true,false}
|Action Property|Whether this Action demonstrates usage of any [ap.](https://doc.gravio.com/manuals/gravio4/1/en/topic/available-variables-in-action#Action%20Property) variables| {true,false}|
|Action Value|Whether this Action demonstrates usage of any [av.](https://doc.gravio.com/manuals/gravio4/1/en/topic/available-variables-in-action#Action%20Variable) variables| {true,false}|
|Trigger Property|Whether this Action demonstrates usage of any [tp.](https://doc.gravio.com/manuals/gravio4/1/en/topic/triggervalandtriggerprop#Trigger%20properties) fields| {true,false}|
|Trigger Value|Whether this Action demonstrates usage of any [tv.](https://doc.gravio.com/manuals/gravio4/1/en/topic/triggervalandtriggerprop#Trigger%20variable) fields| {true,false}|
|Formula|Whether this Action demonstrates usage of any [formula](https://doc.gravio.com/manuals/gravio4/1/en/topic/functions-in-mappings) functions|{list of any valid function}|
|Hardware|Whether this Action relies on other Gravio hardware, such as the Gravio Light| {list of any other Gravio hardware}




# Repo Notes

## Structure of this Repo

This repo is separated primarily into branches for Gravio 5, Gravio 4 and Gravio 3. We know that not everyone will upgrade at the same speed, so we keep older Actions around for those scenarios. 

Within each main branch, the branch splits between Community and Official folders. If you only want officially created sample Actions, go with the Official path. If you want to see what our community has to offer, check out the Community path. 

This repo will be updated with more branches if and when backwards-incompatible versions are released.

## Version Compatability 
Some versions of Gravio are not backwards compatable. For example. 3.8 Actions are not compatable with 4.1 Actions. If we release a major update to Gravio and don't include a new folder here, it can be assumed that the Actions _are_ compatable and may be used freely. If we do include a new folder, then you should assume they _are not_ compatable and should use the folder closest to the version you use that doesn't go over.



# Contributing

## Submitting an Action or Trigger for the Showcase
If you'd like to submit something for us to include in the Showcase, please submit a pull request with your added .acs or .gac files in the appropriate location, and include an edit to the relevent README.md file that contains the full annotations for your submission.

If you do not have a GitHub account or cannot make a pull request, please ping any of the people in the [Gravio Slack Channel](https://gravio-community.slack.com/ssb/redirect) with `(Asteria)` in their name and we'll get it added. If we're all offline, ping us anyway.

### Submission Location
Community should be under the respective versions in the `Community` folder.

### Naming Scheme
We try to use a Snake Case scheme for the filenames of Actions and their folders for increased readability E.g., `Set_Gravio_Light_To_Green.acs`, or `Send_Url_To_Slack.acs`. Only ascii filesnames are accepted.

### Licence
Material made available here is freely licensed for use by anyone under the MIT licence. Any community submissions are subject to this licence. Unless otherwise specified in the [exceptions.txt](/exceptions.txt) file, neither Asteria Corporation, community submitters, nor users of the submissions retain any ownership of the submitted material.

## Other contributions
We welcome pull requests for other things like documentation updates or typos as well.