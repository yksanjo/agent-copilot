# agent-copilot-analyzer

> Service: analyzer for AI Copilot for Developers

## Installation

```bash
npm install @agent-copilot/agent-copilot-analyzer
```

## Usage

```javascript
import { AgentCopilotAnalyzer } from '@agent-copilot/agent-copilot-analyzer';

const service = new AgentCopilotAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
