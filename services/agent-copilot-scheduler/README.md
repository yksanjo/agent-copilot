# agent-copilot-scheduler

> Service: scheduler for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-scheduler
```

## Usage

```javascript
import { AgentCopilotScheduler } from '@agent-copilot/agent-copilot-scheduler';

const service = new AgentCopilotScheduler();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
