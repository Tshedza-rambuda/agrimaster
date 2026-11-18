# AgriMaster — Community Fruit Preservation Prototype

AgriMaster is a responsive, browser-based prototype for a community fruit-preservation facility. It demonstrates how a facilitator can register farmer harvests, monitor a simulated drying environment, track processing stages, record community knowledge and manage a simple product-stock register.

## Run locally

Open `index.html` in a modern browser. No build tools, package installation or server are required.

## Publish with GitHub Pages

1. Open this repository's **Settings**.
2. Select **Pages** in the left navigation.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for GitHub Pages to publish the site. The public URL will appear in the Pages settings.

## Prototype features

- Responsive dashboard and navigation
- English / Tshivenda language toggle (demonstration translations)
- Simulated temperature, humidity and solar-availability readings with status alerts
- Fruit-batch registration and facilitator-controlled processing stages
- Confirmation before marking a batch preserved
- Indigenous Knowledge Systems (IKS) notes with a consent checkbox
- Product-stock records and CSV export of batch records
- Browser-local persistence using localStorage

## Important limitations

This is a **demonstration prototype**, not a production food-safety or facility-control system.

- Sensor readings are randomly simulated. No physical sensors, microcontrollers, displays, alarms or buzzers are connected.
- Temperature and humidity readings do not prove that fruit is safely dried. Use validated food-safety procedures and suitable moisture / water-activity testing.
- Records are stored only in the current browser on the current device. There is no shared database, authentication, user roles, cloud backup or multi-device synchronization.
- Product stock and prices are planning records only. There is no payment gateway, ordering, marketplace transaction or verified financial reporting.
- The IKS examples are introductory prompts. Community knowledge should be recorded and shared only with permission and proper attribution.
- Do not use this demo to control real drying equipment or make food-safety decisions.

## Next steps for a real deployment

Before real-world use, connect calibrated sensors and a tested controller, design safe fail states and audible/visual alarms, validate drying profiles per fruit and equipment, add secure server-side storage and authentication, implement backups and audit logs, and test the system with farmers and food-safety specialists.

## License

No license has been added. Add a license file if you want to specify reuse permissions.
