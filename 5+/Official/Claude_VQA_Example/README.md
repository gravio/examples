# Gravio Action send a VQA (Visual Questions Answer) request to Claude/Antropic
This Gravio action reads an image from an URL and sends it to Claude/Antropic claude-3-5-sonnet-20240620 for VQA (Visual Question Answering) interrogation

## Requirement
- Gravio
- Antropic/Claude API Key

## Installation
- Import the `acs` file into the Gravio Actions editor
- add your `API Key` - You can sign up for Claude following [these instructions on how to obtain your Antropic API Key](https://doc.gravio.com/manuals/gravio4/1/en/topic/anthropic-api-key)
- you will receive the reply from Antropic in the `cv.Payload` variable at the end of the action for further processing
