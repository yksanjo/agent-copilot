# agent-copilot-sdk

> Package 3: sdk for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-sdk
```

## Usage

```javascript
import { AgentCopilotSdk } from '@agent-copilot/agent-copilot-sdk';

const service = new AgentCopilotSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
