# 勘误表

页数		| 章节		| 位置									| 原文								| 更正								| 读者					| 更正版次
------- | --------- | ------------------------------------- | --------------------------------- | --------------------------------- | --------------------- | ---------
VII		| 前言		| 第二段话								| 前18章的代表						| 前18章的代码						| ![moon][moon]			| 
11		| 2.2		| 第一段话第二行							| 。。。件：第二，						| 。。。件；第二，						| ![moon][moon]			| 
12		| 2.2.1		| 第三段话								| 调式信息							| 调试信息							| ![泡泡][泡泡]			| 
21		| 2.3.3		|[末尾倒数第7行代码][p21]					| `CSZIET_SIZE`						| `CSIZET_SIZE`						| ![小灰先生][小灰先生]	| 
29		| 2.4.2		|[末尾倒数第3行代码][p29]					| `CSZIET_SIZE`						| `CSIZET_SIZE`						| ![小灰先生][小灰先生]	| 
104		| 6.2.4		|[LEN指令实现代码][p104]					| `func _len(...)`					| `func length(...)`				| ![小灰先生][小灰先生]	| 
144		| 8.2.1		|[luaStack结构体][p144]					| `closure *luaClosure`				| `closure *closure`				| ![小灰先生][小灰先生]	| 
145		| 8.2.1		|最后一段话								| 。。。vararg字段用于。。。			| 。。。varargs字段用于。。。			| ![moon][moon]			| 
160		| 8.4.6		| 第一段话第二行							| 。。。面相对象体系。					| 。。。面向对象体系。					| ![泡泡][泡泡]			| 
177		| 9.3.1		| `GetGlobal()`第二种实现					| `return self.GetField(t, name)`	| `return self.GetField(-1, name)`	| ![泡泡][泡泡]			| 
236		| 13.1		| 倒数第二段话第一行						| 。。。允许我们再有且仅。。。			| 。。。允许我们在有且仅。。。			| ![泡泡][泡泡]			| 
263		| 13.3.8	| [`NextToken()`方法][p263]和下面的文字	| `isLatter()`						| `isLetter()`						| ![泡泡][泡泡]			| 
290		| 16.1.2	| 图16-2									| 上下文无言							| 上下文无关							| ![moon][moon]			| 
369		| 19.1		| 第二段话								| 。。。定义数据库开启函数，			| 。。。定义数学库开启函数，			| ![泡泡][泡泡]			| 
377		| 19.5		| 第三段话第二行							| 。。。创建lib_os.go.go文件，			| 。。。创建lib_os.go文件，			| ![泡泡][泡泡]			| 

[moon]: readers/moon.png?raw=true "moon"
[泡泡]: readers/paopao.jpeg?raw=true "泡泡"
[小灰先生]: readers/小灰先生.jpeg?raw=true "小灰先生"

[p21]: code/go/ch02/src/luago/binchunk/binary_chunk.go#L9
[p29]: code/go/ch02/src/luago/binchunk/reader.go#L70
[p104]: code/go/ch06/src/luago/vm/inst_operators.go#L100
[p144]: code/go/ch08/src/luago/state/lua_stack.go#L8
[p263]: code/go/ch14/src/luago/compiler/lexer/lexer.go#L204
