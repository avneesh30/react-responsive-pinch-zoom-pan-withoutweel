# react-responsive-pinch-zoom-pan-withoutweel

A React component that adds pinch-zoom and pan capability to an `<img>` element. Both mobile and desktop browsers are supported. On desktop browsers, zoom is triggered via the mouse scrollwheel.

Zoom and pan are applied using CSS transforms. 

## Install

`npm install react-responsive-pinch-zoom-pan-withoutweel --save`

## Try it out

### Online

[Demo](https://bradstiff.github.io/react-responsive-pinch-zoom-pan-withoutweel/)

### Local

1. `git clone https://github.com/bradstiff/react-responsive-pinch-zoom-pan-withoutweel.git`
2. `cd react-responsive-pinch-zoom-pan-withoutweel`
3. `npm install`
4. `npm start`
5. Browse to http://localhost:3001

## Usage

```javascript
import React from "react";
import PinchZoomPan from "react-responsive-pinch-zoom-pan-withoutweel";

const App = () => {
    return (
        <div style={{ width: '500px', height: '500px' }}>
            <PinchZoomPan>
                <img alt='Test Image' src='http://via.placeholder.com/750x750' />
            </PinchZoomPan>
        </div>
    );
};
