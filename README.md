# AutoSizeFormClass
Winform控件自适应

---

###使用方法：
1.项目引入AutoSizeFormClass.dll

2.Form中添加即可
```
        private AutoSizeFormClass asc = new AutoSizeFormClass();

        private void Form1_Load(object sender, EventArgs e)
        {
            asc.controllInitializeSize(this);
        }

        private void Form1_SizeChanged(object sender, EventArgs e)
        {
            asc.controlAutoSize(this);
        }
```
