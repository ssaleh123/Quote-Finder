A web app that identifies movie or TV quotes and automatically corrects them to their exact official wording using a **Cloudflare Worker** powered by an **OpenAI API key**. It returns the verified quote, character, actor, and source in a clean JSON-driven format for accurate quote recognition.

## Features

- Accepts partially accurate or paraphrased quotes.
- Corrects quotes to their official wording.
- Provides character, actor, and source information.
- Powered by a Cloudflare Worker using OpenAI for reliable AI responses.
- Minimalist, user-friendly web interface.

## Usage

1. Open the app in your browser.
2. Type a quote from a movie or TV show in the input box.
3. Click **Identify Quote**.
4. The app will display the corrected quote along with character, actor, and source.

## Technology Stack

- HTML, CSS, JavaScript (frontend)
- Cloudflare Worker (serverless backend)
- OpenAI API (for quote verification and correction)

## Example

Input:  
we are going to need a bigger boat

Output:  
Quote: "You're gonna need a bigger boat."
Character: Martin Brody
Actor: Roy Scheider
Source: Jaws
