# agent-copilot-api

> Package 2: api for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-api
```

## Usage

```javascript
import { AgentCopilotApi } from '@agent-copilot/agent-copilot-api';

const service = new AgentCopilotApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
