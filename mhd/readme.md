svg做icon 
icon可以用图片但是体积大，要下载。
而svg是字节，图片是KB 图标就用SVG
- stroke-dasharray: 90 310;/***重要考点  dasharray虚线 第一个参数是实的有多少，第二个参数是一共有多少*/
stroke-dashoffset: -400;/* 偏移量，实线起点偏移-400*/
- animation-delay: -1.5s;/* 提前1.5s运动*/


- margin: 0 auto;/* 自动居中 */
- .grid:before{     /* 伪元素一定要有content属性 */
        content:"";
    }
- xmlns="http://www.w3.org/2000/svg" 命名空间用来跟html中的其他命名隔离开来