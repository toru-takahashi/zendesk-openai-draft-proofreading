# Zendesk OpenAI Draft Proofreading

This Zendesk App (Zendesk OpenAI Draft Proofreading) helps Zendesk Agent to write and proofread a draft of your ticket response by using OpenAI.

### Prerequire

- [OpenAPI Paid APIKEY](https://platform.openai.com/account/api-keys)

### How to use

1. Install this app via Zendesk Marketplace
2. Set OpenAI's APIKEY in the app setting

![README](./readme.png)

3. In Zendesk Ticket view, select one of 4 options;

- Draft (ja): Send the ticket conversation to OpenAI and then insert the generated response in Japanese to the comment
- Proofread (en): Send a text in the ticket comment to OpenAI and then insert the reviewed response  in Japanese to the comment
- Draft (ja): Send the ticket conversation to OpenAI and then insert the generated response in English to the comment
- DrProofreadaft (en): Send a text in the ticket comment to OpenAI and then insert the reviewed response  in English to the comment

![README](./readme-1.png)

4. This app automatically inserts the response to the text box.

![README](./readme-2.png)


## License

This repository is licensed under the Apache 2.0 License.

