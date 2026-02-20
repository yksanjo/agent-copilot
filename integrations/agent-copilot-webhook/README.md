# agent-copilot-webhook

> Integration: webhook for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-webhook
```

## Usage

```javascript
import { AgentCopilotWebhook } from '@agent-copilot/agent-copilot-webhook';

const service = new AgentCopilotWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
