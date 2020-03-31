# HW2 Lesson Learn:

There are several leraning lessons from this week's HW.<br>
1. 計算債券每一期的spot rate的時候，想像他是多個零息債券所組成:<br>
我一開始在思考的時候試著要從該債券每一期當下結算的YTM下手，但如此計算上會變得非常複雜，因為除了第一年的YTM等於spot rate之外，剩下的都必須考慮複利的狀況。改用零息債券組合來思考債券較容易了解與計算。<br>

2. 利用Python解方程式(在解YTM和Spot rate時會用到):<br>
可以透過scipy當中的optimize解方程式，記得將方程式中的所有項移到同一側，存成一個變數，並給予一個初始猜測值(使用牛頓法)。例如:<br>
```` optimize.newton(ytm_func, guess)````<br>

3. 在財務的領域如果利率要以"年"作為單位表示(即使這個債券為半年到期的債券)。

4. 如果要print一串文字和某個你算出來的變數，可以使用.format()的方式，展示如下:<br>
```` print("The YTM of the bond is: {}.".format(ytm))````<br>

5. 我在寫迴圈使用range()產生一串數列的時候，range當中要輸入的數值要是整數，python不接受浮點數。<br>
```` for i in range(int(periods)): ````<br>


