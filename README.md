# eldialog
 v-dialogDrag: 弹窗拖拽+水平方向伸缩
/*

*  使用方法

*  将以下代码复制到一个js文件中，然后在入口文件main.js中import引入即可；

*  给elementUI的dialog上加上 v-dialogDrag 指令就可以实现弹窗的全屏和拉伸了。

*  给dialog设置 :close-on-click-modal="false" , 禁止点击遮罩层关闭弹出层

*  如果是form表单，不要将提交等按钮放置el-form-item，以免在上下拉伸时被隐藏


 <el-dialog v-dialogDrag title="弹窗" width="680px" ></el-dialog>