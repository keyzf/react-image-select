# react-image-select
An Image Select control built with and for React JS


# get started
## 1. install
```javascript
npm install react-image-select
```

## 2. import
```javascript
import ImageSelect from 'react-image-select';
```

## 3. use
```javascript
<ImageSelect
  images={['/images/apple.png', '/images/banana.png', '/images/pear.png']}
  width={20}
  height={20}
  defaultIndex={2} // will select pear.png
  onChange={this._handleChange}/>
```
