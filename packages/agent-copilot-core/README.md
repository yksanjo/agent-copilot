# agent-copilot-core

> Package 1: core for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-core
```

## Usage

```javascript
import { AgentCopilotCore } from '@agent-copilot/agent-copilot-core';

const service = new AgentCopilotCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
