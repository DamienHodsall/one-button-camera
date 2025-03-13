# one-button-camera

The goal of this project is to give users a simple way to share their projects. To do this we are making a "one button camera"; a device that can take pictures, prompt to select the best picture, get a description, and share the project details to makerspace staff via the makerspace email.

# TODO

- [ ] make a better TODO list

# Requirements

- Take multiple images
- Choose best image for future post
- Prompt for the following:
    - email
    - consent to post
    - name
    - consent to share name in post
    - TID?
    - project name
    - project description
- Send above to makerspace
- Send image(s) to given email
- make with the following:
    - raspberry pi
    - touchscreen
    - 3d printed case (probably)

# Design

- locally hosted web server
    - forms are easy with html/javacsript
    - easy to scale to web app
    - camera part is already built
    - takes a few more steps to start than a python approach
