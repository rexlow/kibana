## Changes Made for Revenue Monster Admin Portal

### Dashboard UI

1. Update dashboard background color

	> `src/ui/public/styles/variables`

	```
	@dashboard-bg-with-margins: #F5F5F5;
	
	to
	
	@dashboard-bg-with-margins: #f0f2f5;
	```
	
2. Hid filter bar

	> `src/ui/public/filter_bar`
	
3. Hid kibana loading indicator

	> `src/ui/public/chrome/directives/kbn_chrome.html`
	
4. Hid TagCloud feedback message

	> `src/core_plugins/tagcloud/public/feedback_message.js`