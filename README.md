# typesense-on-render
Deploy [Typesense](https://typesense.org/) on [Render.com](https://render.com)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


## Environment Variables
- `TYPESENSE_API_KEY` -- A bootstrap admin API key that allows all operations. Be sure to create additional keys with specific ACLs using the [key management API](https://typesense.org/docs/0.21.0/api/api-keys.html). (Default = `{randomly_generated_key}`)
- `TYPESENSE_DATA_DIR` -- Path to the directory where data will be stored on disk. Probably don't need to change this, as it's also in the render.yaml (Default = `/typesense-data`)
- `TYPESENSE_ENABLE_CORS` -- Allow JavaScript client to access Typesense directly from the browser. (Default = `true`)

See full list of options you can configure [here](https://typesense.org/docs/0.21.0/guide/configure-typesense.html)