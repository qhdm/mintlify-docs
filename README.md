# Mintlify Starter Kit

<div style="background-color: #2196f3; padding: 8px 12px; border-radius: 4px 4px 0 0; color: white; font-weight: bold;">
  Problem 2.6: Experiments with tokenizers (4 points)
</div>
<div style="border: 1px solid #2196f3; padding: 12px; border-radius: 0 0 4px 4px;">

(a) Sample 10 documents from TinyStories. Using your previously-trained TinyStories tokenizers (10K vocabulary size), encode these sampled documents into integer IDs. What is the tokenizer's compression ratio (bytes/token)?

(b) Estimate the throughput of your tokenizer (e.g., in bytes/second). How long would it take to tokenize the Pile dataset (825 GB of text)?

(c) Using your TinyStories tokenizers, encode the respective training and development datasets into a sequence of integer token IDs. We'll use this later to train our language model. We recommend serializing the token IDs as a NumPy array of datatype uint16. Why is uint16 an appropriate choice?
</div>

Use the starter kit to get your docs deployed and ready to customize.

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
