![img](/assets/images/the_symbolic_survival_of_the_master_and_margarita_1050x700.jpg)

(c) An illustration of the cat Behemoth from The Master and Margarita Getty 

# Nikolay Tiushkov

================================

## Contacts:

**Phone**: +000 12 345-67-89
**E-mail**: begemot@begemotov.net
**Telegram** : [TNikolay80](https://t.me/TNikolay80)
**GitHub**: [TNikolay](https://github.com/TNikolay)

## About

Human. Still alive.

## Skills

A lot... a little bit... Who knows?...

Scio me nihil scire

## Links

* **Work** : [softvoile.com](http://softvoile.com/)
* **Private** : [begemotov.net](http://begemotov.net/)
* **Playground** : [leetcode.com](https://leetcode.com/TNikolay/)

## Code
```Kotlin

class Solution {
    fun closeStrings(word1: String, word2: String): Boolean {

        if (word1.length != word2.length) return false

        val a1: Array<Int> = Array(26, {0})
        val a2: Array<Int> = Array(26, {0})

        for (w in word1) ++a1[w.toInt() - 97]
        for (w in word2) ++a2[w.toInt() - 97]

        for (i in a1.indices) 
            if (a1[i] == 0 && a1[i] != a2[i]) return false

        a1.sort()
        a2.sort()

        return a1.contentEquals(a2)
    }
}
```

## Languages:

* **Russian** - native
* **Ukrainian** - intermediate
* **English** - in progress