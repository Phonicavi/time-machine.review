###哈希方法  
	建一个数组array 由于所有出现的字符都只能是小写 且是字母 所以数组长度设为26  
	先比较两个字符串长度 不一样肯定不同  
	两个字符串长度一样的情况下
		- 扫过第一个字符串s 每遇到一个字母就在这个位上加1  
		- 扫过第二个字符串t 每遇到一个字母就在这个位上减1  
	检查array数组 如果所有位都为0说明完全相同 返回true(否则说明false)  