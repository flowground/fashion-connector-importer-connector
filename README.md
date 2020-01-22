# ![LOGO](logo.png) Fashion Connector Importer **flow**ground Connector

## Description

A generated **flow**ground connector for the Fashion Connector Importer API (version 0.1.0).

Generated from: https://merchants-connector-importer.zalandoapis.com/<br/>
Generated at: 2020-01-22T11:26:18+00:00

## API Description

Set of adapters which allow partners to send their stock and price updates into Zalando Platform.<br/>

## Authorization

Supported authorization schemes:
- API Key


## Actions

### Process a stock/price update
> Receives a valid stock/price update file (CSV) and<br/>
> queues it for processing.<br/>

#### Input Parameters
* `file_name` - _required_ - Stock/price update file name<br/>
* `client_id` - _required_ - Partner client id<br/>

### Validate the stock/price update file (CSV)
> Receives a valid stock/price update file (CSV) and<br/>
> validates it.<br/>

#### Input Parameters
* `client_id` - _required_ - Partner client id<br/>

## License

**flow**ground :- Telekom iPaaS / fashion-connector-importer-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
