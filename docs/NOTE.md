# Note


## Scopes

- Languages: Vietnamese, English
- Content-Type: Text, Image
    - At early stage: audio is processed via speech-to-text model. Do not handling edge-cases like speaker's intention, ...; video is considered as image + audio.

- Features:
    1. Harmful content detection (Text, Image).
        - Toxicity, hate speech, etc.
        - Nudity, etc.
    2. Identify personal information (Text).
        - Name, phone number, email, etc.
    3. Return dataset, which is used for model training.
    4. Integrate LLM, VLM (focus on small or very small models), and allow users to use their prompts or to initial prompts (they have rights to seen those prompts' templates).


## Constraints

- 
