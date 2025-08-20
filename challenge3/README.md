# Week 3 Challenge - ElevenLabs x MCP Integration

## Overview
Week 3 is all about combining ElevenLabs with the Model Context Protocol (MCP) to create powerful voice and tool integrations. Choose your own adventure with three different paths to explore!

## Challenge Theme: "Voice x MCP"
Build something creative that showcases the power of combining ElevenLabs with MCP. Whether you're enhancing productivity, creating entertainment, or solving real problems - the goal is to demonstrate meaningful integration between voice/audio and tools.

## Three Ways to Participate

Choose the approach that excites you most - all are judged equally on merit:

### Option 1: Use the ElevenLabs MCP Server
Integrate the [official ElevenLabs MCP server](https://github.com/elevenlabs/elevenlabs-mcp) into your workflow or application. Use it to:
- Generate speech from your LLM applications
- Create audio content programmatically
- Build voice-enabled tools and workflows

### Option 2: Build an MCP Server Using ElevenLabs API
Create your own MCP server that leverages the ElevenLabs API to:
- Provide text-to-speech capabilities as MCP tools
- Integrate voice generation into existing tool chains
- Create custom audio processing workflows

### Option 3: Integrate MCP Servers with Conversational AI
Build a voice agent using ElevenLabs Conversational AI that connects to MCP servers to:
- Execute real-world tasks through voice commands
- Access external data and services
- Create interactive voice assistants with tool capabilities

## Requirements

### Core Requirements (All Options)
* Meaningful integration between ElevenLabs and MCP
* Clear demonstration of value/utility
* Public deployment/accessibility for judging

### Option-Specific Requirements
* **Option 1**: Must use the official ElevenLabs MCP server in a creative application
* **Option 2**: MCP server must be deployed and accessible via public URL
* **Option 3**: Conversational AI agent must be publicly shareable with integrated MCP tools

## Getting Started

### Quick Links
- [ElevenLabs Quickstart](https://elevenlabs.io/docs/quickstart)
- [ElevenLabs MCP Server](https://github.com/elevenlabs/elevenlabs-mcp)
- [Conversational AI MCP Integration](https://elevenlabs.io/docs/conversational-ai/customization/mcp)

### For Conversational AI + MCP (Option 3)
1. Create an agent in the [Conversational AI dashboard](https://elevenlabs.io/app/conversational-ai)
2. Add your MCP server via [Integrations](https://elevenlabs.io/app/conversational-ai/integrations)
3. Configure tool approval modes and test your integration

### For Custom MCP Servers (Options 1 & 2)
Integrate the ElevenLabs SDK into your Cloudflare Worker/ MCP server. Your API endpoint should either:
- Return the audio file directly as an MP3 download when calling the endpoint
- Or additionally store it in a Cloudflare R2 bucket (Codegen can help set up the bucket for you)

## Submission
- Project/ Application Description
- Explain your voice application's purpose
- A link to your deployed application.
- API Documentation: Some instructions on how to use your voice application/ API (we need to be able to fetch the generated audio file)
- A link to your Fiberplane Codegen Project
- (Optional): a link to a github repo
- Use [this form](https://forms.gle/s4eFfMWBF5Q273Zr9) to submit your challenge

### Deadlines
- Deadline for the challenge prize, Wednesday, August 21st, 2025, 11:59 PM (PT)
- You can submit challenges after the deadline to unlock items for the final swag bag until the end of Vibe Summer (August 28th, 2025, 11:59 PM (PT))

## Evaluation Criteria

- **Innovation** (25%): How creative and novel is your implementation?
- **Technical Excellence** (25%): Code quality, architecture etc
- **User Experience** (25%): How intuitive and polished is the final product?
- **Impact/Utility** (25%): Does it solve a real problem?

## Resources

- [ElevenLabs Documentation](https://elevenlabs.io/docs)
- [Our mcp server](https://github.com/elevenlabs/elevenlabs-mcp)
- [MCP server integration in Conversational AI](https://elevenlabs.io/docs/conversational-ai/customization/mcp)
