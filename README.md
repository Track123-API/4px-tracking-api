# 4PX Tracking API & Webhooks

Use Track123 to track 4PX shipments through one unified shipment tracking API.

Track123 lets your application register 4PX tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- 4PX carrier code: `4px`

- [Track 4PX packages on Track123](https://www.track123.com/carriers/4px)

- [4PX API integration page](https://www.track123.com/carriers/4px/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track 4PX shipments with Track123. It is not official 4PX API documentation.

## 4PX tracking API integration

When your application already knows that a shipment is handled by 4PX, set `courierCode` to `4px` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [4PX tracking webhook](webhook.md)
- [4PX tracking statuses](tracking-status.md)
- [4PX API errors and rate limits](errors-and-rate-limits.md)

## 4PX tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track 4PX packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [4PX tracking on Track123](https://www.track123.com/carriers/4px).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by 4PX unless explicitly stated.
