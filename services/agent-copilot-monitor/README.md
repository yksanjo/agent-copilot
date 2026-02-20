# agent-copilot-monitor

> Service: monitor for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-monitor
```

## Usage

```javascript
import { AgentCopilotMonitor } from '@agent-copilot/agent-copilot-monitor';

const service = new AgentCopilotMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
