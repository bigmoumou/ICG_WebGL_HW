# ICG_WebGL_HW
Demo code of Interactive Computer Graphics 2018 Fall (ICG)

### Shading :
- Flat shading demo:    
  https://bigmoumou.github.io/ICG_WebGL_HW/flat_shading/
- Gourand shading demo:    
  https://bigmoumou.github.io/ICG_WebGL_HW/gourand_shading/
- Phong shading demo:    
  https://bigmoumou.github.io/ICG_WebGL_HW/phong_shading/
- Toon shading demo:    
  https://bigmoumou.github.io/ICG_WebGL_HW/toon_shading/

### Transformations :
- Rotation:    
```javascript
    function degToRad(degrees) {
        return degrees * Math.PI / 180;
    }
    // rotate on x-axis:
    mat4.rotate(mvMatrix, degToRad(teapotAngle), [1, 0, 0]);
    // // rotate on z-axis:
    // mat4.rotate(mvMatrix, degToRad(teapotAngle), [0, 0, 1]);
    // // rotate on both x and y-axis together:
    // mat4.rotate(mvMatrix, degToRad(teapotAngle), [1, 1, 0]);
```
  
