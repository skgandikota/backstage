## API Report File for "@backstage/backend-defaults"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { DiscoveryService } from '@backstage/backend-plugin-api';
import { RootConfigService } from '@backstage/backend-plugin-api';
import { ServiceFactory } from '@backstage/backend-plugin-api';

// @public
export const discoveryServiceFactory: ServiceFactory<
  DiscoveryService,
  'plugin',
  'singleton'
>;

// @public
export class HostDiscovery implements DiscoveryService {
  static fromConfig(config: RootConfigService): HostDiscovery;
  // (undocumented)
  getBaseUrl(pluginId: string): Promise<string>;
  // (undocumented)
  getExternalBaseUrl(pluginId: string): Promise<string>;
}

// Warnings were encountered during analysis:
//
// src/entrypoints/discovery/HostDiscovery.d.ts:44:5 - (ae-undocumented) Missing documentation for "getBaseUrl".
// src/entrypoints/discovery/HostDiscovery.d.ts:45:5 - (ae-undocumented) Missing documentation for "getExternalBaseUrl".

// (No @packageDocumentation comment for this package)
```