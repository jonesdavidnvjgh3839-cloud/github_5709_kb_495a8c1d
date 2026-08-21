# Quickstart

Get up and running with **Nimbus Analytics** in a few minutes.

## Step 1: Install the SDK

Add the Nimbus Analytics SDK to your web or mobile application using your package manager.

## Step 2: Initialize tracking

Initialize the SDK with your workspace token and start sending events:

```js
import { init, track } from '@nimbus-analytics/sdk';

init({ token: 'YOUR_WORKSPACE_TOKEN' });
track('page_viewed', { page: 'pricing' });
```

## Step 3: View your data

Open the Nimbus Analytics dashboard to explore real-time events, funnels, and retention analysis.

## Next steps

- Read the [installation guide](../docs/installation.md) for deployment options.
- Explore the [API reference](../docs/api-reference.md) for advanced integrations.
