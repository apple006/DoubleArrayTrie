# DoubleArrayTrie
双数组字典树的实现

本双数组实现字符串查找的基本算法是
next_sub = base[cur_sub] + next_var_seq
check[cur_sub] = pre_sub
主要是字符之间的状态传递实现


使用方法
KeyWordResult result = KeyWordMatch.matchKeyWord("代理办证前途无量");
if (result.isContain) {
			for (String keyword : result.getKeywords()) {
				System.out.println(keyword);
			}
	}

首字数量383     ------------  初始加载时
总字数1278      ------------  初始加载时
8192            ------------  初始加载时
8192            ------------  初始加载时
敏感词:办证     ------------  文本敏感词

未完成功能：
1 词级别控制