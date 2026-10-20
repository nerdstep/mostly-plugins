# Mostly Recipes

Save recipes from your conversations with Claude to your
[Mostly Recipes](https://mostly.recipes) cookbook.

## What it does

This plugin connects Claude to Mostly Recipes and adds two skills that tell
Claude how to use it:

- **save-recipes**: saves a recipe you worked out together, a recipe you paste
  or photograph, or one from a public recipe link. Claude saves each recipe
  once and tells you where to find it.
- **saved-recipes**: lists the recipes Claude saved for you and reopens one,
  with its ingredients and steps.

Saved recipes appear in your cookbook the next time you open Mostly Recipes.
Claude can see only the recipes it saved. It can't see, change, or delete your
other recipes.

## Use it

1. Install the plugin, then connect Mostly Recipes from the plugin's
   Connectors tab.
2. Sign in to your Mostly Account and approve the connection.
3. Ask Claude to save a recipe, for example:
   - "Save this recipe to Mostly Recipes."
   - "Create a weeknight vegetarian chili recipe and save it to Mostly Recipes."
   - "Show the recipes you've saved to my Mostly Recipes cookbook."

You need a Mostly Account. The plugin works in Claude on the web, desktop, and
mobile, and in Cowork. Claude Code can't sign in to Mostly Recipes yet.

## Data

The plugin itself runs no code and stores nothing. It points Claude at the
Mostly Recipes server, `https://mostly.recipes/mcp`, which you sign in to with
OAuth. When you ask Claude to save a recipe, it sends the recipe's title,
ingredients, steps, and source web address to your Mostly Recipes account.
When you ask it to save a recipe link, Mostly Recipes fetches that page to read
the recipe. Read the
[privacy policy](https://mostly.recipes/legal#ai-assistants) for what Mostly
Recipes stores and for how long.

You can disconnect Claude anytime in Mostly Recipes, under your account's AI
assistants. Recipes it already saved stay in your cookbook.

## Support

Email [support@mostly.recipes](mailto:support@mostly.recipes) or use the
[contact form](https://mostly.recipes/contact?topic=ai-assistants).

## License

[MIT](LICENSE)
