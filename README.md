# ScratchTools Docs
These are the **Official** docs for the ScratchTools extension for Scratch.

# Getting Started
Welcome to ScratchTools! We'll get you started with ScratchTools!

## Download
You can easily download ScratchTools from 3 different places:
- [Chrome Web Store](https://chrome.google.com/webstore/detail/scratchtools-for-scratch/jjnpbalpllpfdpgplpbcbadkgdmleopm)
- [Mozilla Web Store](https://addons.mozilla.org/en-US/firefox/addon/scratchtools-for-scratch/)
- [GitHub, from the source](https://github.com/rgantzosonscratch/ScratchTools/)

## Setting Up
Once you download ScratchTools, you still get to customize what ScratchTools looks like for you! Go to the [ScratchTools Settings](https://scratch.mit.edu/ScratchTools/) (the page will only show if have ScratchTools downloaded) and then choose which features you want on and off!

# Development
We have a rule when it comes to developing new features for ScratchTools, and it's "the more the merrier"! It's easy to work with ScratchTools, and there's always a job for everyone!

## How to Help
If you just want to help us occassionally, and you want to have a small part in ScratchTools, that's absolutely fine! We love it when people help us, no matter how much! You can report a bug or slip us a suggestion on our [Community Discord Server!](https://discord.gg/rwAs5jDrTQ)

### Jobs
If you want a more solid, laid out way to help ScratchTools, then there's also a place for you! We have tons of jobs, one for everybody. Here are some of them:
- Programmer (This person can know JavaScript, or even just Scratch)
- Brainstormer
- Artist
- Press Release (Helps get ScratchTools popular)
- Website/Other Help

You can easily apply for any job on our [Community Discord Server!](https://discord.gg/rwAs5jDrTQ)

## Building a Feature
Creating features for ScratchTools is very easy, and we even teach people how to code them on our [Community Discord Server!](https://discord.gg/rwAs5jDrTQ)

### About Features
ScratchTools features are anything that manipulate (or change) Scratch to make it easier or better for certain users. The more users that the feature is helpful for, the more likely it is to be accepted.

To completely create a feature, you'll need to know JavaScript. You'll most likely also need to know DOM. To learn DOM, you can learn it [here](https://www.w3schools.com/js/js_htmldom.asp) or [we can teach you.](https://discord.gg/rwAs5jDrTQ) If you're ready to continue past this step, then it's time to head over to [our repository.](https://github.com/rgantzosonscratch/ScratchTools/)

### Forking
To start building your feature, head over to [our repository.](https://github.com/rgantzosonscratch/ScratchTools/) In the top right corner (adjacent to the repository title) you'll see multiple buttons. You're going to fork the repository.

### Coding
Now it's time for you to start coding your feature. But wait! There are still some formatting rules when you create your feature. In your fork, you'll see a few folders and a few separate files. You're only going to deal the folder titled "features" for now. You're going to open up that folder, and add a new file. That file will hold all the code for your feature. Make sure to name it something that accurately represents what your feature does. Then, add the code for your feature.

### Adding the Info
Next, open up the file called features.json inside of your fork. You're going to add the info for your new feature. Below where it says "add new features below here", add your version of the following:

```
{
    "title": "this is the title of your feature",
    "description": "describe the feature, what it does, and why it is important",
    "credits": "list each user who helped",
    "urls": "add a link for each user who helped, in the same order"
},
```

Awesome! Once you're done, you only have to do one more thing for your feature! Open up the manifest.json file, and look for this:
```
{
    "matches": ["https://scratch.mit.edu/*"],
    "all_frames": true,
    "js": ["/pages/all.js", "/pages/discuss.js" ... "/features/turbowarp-button.js"],
    "css": [],
    "run_at": "document_end"
}
```

#### For JavaScript Features
At the end of the list of JavaScript files, add this: `/features/your file name`. It should look like this, except example is replaced with the name of your file:
```
{
    "matches": ["https://scratch.mit.edu/*"],
    "all_frames": true,
    "js": ["/pages/all.js", "/pages/discuss.js" ... "/features/turbowarp-button.js", "/features/example.js"],
    "css": [],
    "run_at": "document_end"
}
```

#### For CSS Features
At the end of the list of CSS files, add this: `/features/your file name`. It should look like this, except example is replaced with the name of your file:
```
{
    "matches": ["https://scratch.mit.edu/*"],
    "all_frames": true,
    "js": ["/pages/all.js", "/pages/discuss.js" ... "/features/turbowarp-button.js"],
    "css": ["example.css"],
    "run_at": "document_end"
}
```

### Submitting
Nice job! You're almost done! Head over to the [pull requests section of the original repository](https://github.com/rgantzosonscratch/ScratchTools/pulls) and create a new pull request. Below where it says "Compare changes", click "compare across forks". Switch the head repository to your fork that you made. Then press "create pull request", and give your pull request a title and a description. Then submit it, and that's it! We'll review it and consider your new feature! We may change a few parts if we accept it.

## Beta Testing
We have a large beta program, and we're constantly accepting more people to join. There isn't much of a hiring process, you can just join from our [Community Discord Server!](https://discord.gg/rwAs5jDrTQ) Once you've joined the beta program, you'll get special alerts for new versions in preparation and you'll get early access to new features so that you can test them. If you find a bug, it's easy to report it, and you'll learn how! You get prizes and credit for bugs that you find and are accepted.

# FAQ
Here are some frequently asked questions and how ScratchTools answers them:

## Is ScratchTools available on Firefox?
Yes, ScratchTools is on Firefox. You can download it [here.](https://addons.mozilla.org/en-US/firefox/addon/scratchtools-for-scratch/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)

## Is ScratchTools affiliated with Scratch?
No, ScratchTools is in no way affiliated with Scratch. We are completely different organizations. ScratchTools is only an extension that supports Scratch.

## Are ScratchTools and Scratch Addons the same thing?
No, ScratchTools and Scratch Addons are separate extensions with different creators. There are some developers that are mutual, and who work for both ScratchTools and SA.

## Does ScratchTools cost money?
No, ScratchTools is 100% free and will never ask you for payment information. ScratchTools is easy to use, and without any cost.

## Can I help ScratchTools?
Yes, you absolutely can help ScratchTools! Go [here](https://rgantzosonscratch.github.io/ScratchTools-Docs/#/?id=how-to-help) for more info on how to help! We hope one day you can become a developer with ScratchTools!

## Does ScratchTools have social media?
Yes, ScratchTools is on [Discord](https://discord.gg/rwAs5jDrTQ), [Twitter](https://twitter.com/ST_ForScratch), and [YouTube!](https://www.youtube.com/channel/UCYZiKwxZ_8gJaMwbxHmP0KA) We frequently post info on our Twitter and YouTube, and everything having to do with ScratchTools usually happens on our Discord.
