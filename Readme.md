# Logicalis Style Guide

Based on [Tapestry](https://github.com/PebbleRoad/tapestry)

## Developing
        npm install
        npm start

Got to [http://localhost:8000](http://localhost:8000)

### Build

        npm run build

## Tapestry Pattern format

    ---
    name: Alert
    description: |
        ### What
        Page­ level information or service alert. Critical updates with a defined time period should be pushed using the alert box.
        ### Use when
        For page­level critical updates.
    ---
    <div class="ui-alert ui-alert--success">
        <div class="alert__title">This is a success alert</div>
        <div class="alert__body">More body text</div>
        <a href="#" class="alert_close"></a>
    </div>