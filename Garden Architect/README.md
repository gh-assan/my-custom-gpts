# Garden Architect: Custom GPT Documentation

## General Purpose

Garden Architect is a specialized GPT model designed to assist users in transforming verbal or written garden descriptions into structured garden architecture designs. Its primary function is to convert detailed descriptions, including dimensions, structures, types of trees, flowers, and other garden elements, into a comprehensive JSON document. This document provides all necessary details for creating engineering diagrams, thereby serving as a foundational blueprint for garden development. 

The Garden Architect emphasizes:
- Accuracy and attention to detail in the planning process.
- Creativity in garden design, incorporating cultural and historical elements relevant to the garden's location.
- Providing a structured approach to garden planning to ensure a practical and aesthetically pleasing outcome.

## Best Practices for Use

To make the most out of Garden Architect, users should:
- Provide detailed descriptions of their garden, including its dimensions, preferred plants, paths, water features, and structures.
- Mention any specific cultural or historical themes they wish to incorporate.
- Be clear and comprehensive in their descriptions to avoid the need for clarification.

## Main Commands

Garden Architect operates primarily through user prompts that describe the desired garden. From these descriptions, it generates a JSON document structured as follows:

```json
{
  "garden": {
    "name": "",
    "dimensions": {"length": "", "width": ""},
    "location": "",
    "elements": {
      "plants": [{"name": "", "category": "", "position": {"x": "", "y": ""}}],
      "paths": [{"name": "", "material": "", "points": [{"x": "", "y": ""}]}],
      "waterFeatures": [{"name": "", "category": "", "position": {"x": "", "y": ""}, "dimensions": {"length": "", "width": "", "depth": ""}}],
      "structures": [{"name": "", "category": "", "position": {"x": "", "y": ""}, "dimensions": {"length": "", "width": "", "height": ""}}]
    }
  }
}
```

When using Garden Architect, you do not need to explicitly call commands. Instead, provide a detailed garden description, and the model will automatically interpret this information to generate the JSON document. If you require specific elements to be included in the design, like a certain type of plant or a water feature, mention these in your description.

## Examples of Use

- **Garden Planning**: Describe your garden space, including size, desired plants, and any features like ponds or pergolas, and Garden Architect will provide a structured plan.
- **Cultural Themes**: Mention any cultural or historical themes you want to incorporate, and the model will suggest elements that fit these themes.
- **Creative Inspiration**: Ask for ideas on specific garden styles, like Japanese Zen gardens or English Cottage gardens, and get detailed components that can be included in your design.

Garden Architect provides a unique blend of creativity, precision, and practicality, making garden planning an enjoyable and efficient process.