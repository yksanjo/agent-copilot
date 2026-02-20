# agent-copilot-cli

> Package 4: cli for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-cli
```

## Usage

```javascript
import { AgentCopilotCli } from '@agent-copilot/agent-copilot-cli';

const service = new AgentCopilotCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
