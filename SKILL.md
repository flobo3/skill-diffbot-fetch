{
  "name": "diffbot-fetch",
  "description": "Fetch and extract clean article content from any URL using the Diffbot Article API. Returns clean Markdown.",
  "version": "1.0.0",
  "author": "flobo3",
  "license": "MIT",
  "tools": [
    {
      "name": "diffbot_fetch",
      "description": "Fetch and extract clean article content from any URL using the Diffbot Article API. Use this when you need to read the main text of an article, blog post, or news story without the clutter of ads, navigation, or sidebars.",
      "parameters": {
        "type": "object",
        "properties": {
          "url": {
            "type": "string",
            "description": "The URL of the article to fetch"
          }
        },
        "required": ["url"]
      },
      "command": "python fetch.py \"{{url}}\""
    }
  ]
}
