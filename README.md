remixins for {less}
-
###Automatically convert pixel measures into rem units.

remixins is a collection of {less} mixins that helps you start using rem units without coding pixels fallbacks on every rule. Code your CSS using pixels. remixins will automatically convert them to rem units.

remixins includes {less} mixins for most popular properties where rem is used as a measure unit.

Available mixins for the following CSS properties:  
 * font-size, line-height and text-indent.  
 * margin  
 * padding  
 * height and width  
 * top, left, bottom and right.  

#### How to use it:
1. Download remixins.less
2. Set `@base-font-size-px` to your base root's font size in pixel. Note that `@base-font-size-px` **MUST BE AN INTEGER**.
3. Import downloaded file `@import "remixins.less`.

### Examples:
**{less}:**  
```css
    .element {
        .font-size(16px);
    }
```  
**CSS result:**  
```css
    .element {
        font-size: 16px;
        font-size: 1.6rem;
    }
```

**{less}**  
```css
    .element {
        .margin(10px, 3%);
    }
```  
**CSS result:**  
```css 
    .element {
        margin: 10px 3%;
        margin: 1rem 3%;
    }
```

### Included mixins
* .font-size(@value)
* .line-height(@value)
* .text-indent(@value)
* .margin(@value)
* .margin(@vertical, @horizontal)
* .margin-top(@value)
* .margin-left(@value)
* .margin-bottom(@value)
* .margin-left(@value)
* .padding(@value)
* .padding(@vertical, @horizontal)
* .padding-top(@value)
* .padding-left(@value)
* .padding-bottom(@value)
* .padding-left(@value)
* .height(@value)
* .min-height(@value)
* .max-height(@value)
* .width(@value)
* .min-width(@value)
* .max-width(@value)
* .top(@value)
* .left(@value)
* .bottom(@value)
* .right(@value)

**@chrRamirez**
