# Tabs

### Usage
Here it is the code add 3 tabs on your page. The `data-target` and `data-tab-target` attributes are very important to deal with javascript. Finally `.tabs-active` class is used to select a default tab to show. 
```html
<div class="tabs">
    <ul class="tabs-navigation">
      <li class="tabs-active" data-target="firstTab">First tab</li>
      <li data-target="secondTab">Second tab</li>
      <li data-target="thirdTab">Third tab</li>
    </ul>
    <div class="tabs-content">
      <div class="tabs-item tabs-active" data-tab-target="firstTab">
        <div class="tabs-item-label">
          First tab
        </div>
        <div class="tabs-item-content">
          First content
        </div>
      </div>
      <div class="tabs-item" data-tab-target="secondTab">
        <div class="tabs-item-label">
          Second tab
        </div>
        <div class="tabs-item-content">
          Second content
        </div>
      </div>
      <div class="tabs-item" data-tab-target="thirdTab">
        <div class="tabs-item-label">
          Third tab
        </div>
        <div class="tabs-item-content">
          Third content
        </div>
      </div>
    </div>
  </div>
```

### Javascript
The HTML and CSS is not enough for Tabs, we have to initiate the component with the following code
```javascript
Omicron.AutoInit();

// or if you want load Tabs only.

let instances = Omicron.Tabs.init();
```

### Events
On this component, we can trigger an event to simulate a click on tab link like this exemple:
```javascript
// Trigger event on the second tab's link navigation
$('.tabs .tabs-navigation > li:nth-child(2)').trigger('ev.tab.click');
```

### Options
The `init()` method can accept this options:

| Option name | Type          | Default  |
| ----------- | ------------- | -------- |
| fullWidth   | boolean       | true     |