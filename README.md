# Password-Controls-and-Security-Policies

As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. You often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

# Project Objectuve
What type of hashing algorithm was used to protect passwords?

What level of protection does the mechanism offer for passwords?

What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?

#observations: 
The results that I have got after cracking the passwords using the HASHCAT software are gives as below: 

1.	e10adc3949ba59abbe56e057f20f883e : 123456
2.	25f9e794323b453885f5181f1b624d0b : 123456789
3.	d8578edf8458ce06fbc5bb76a58c5ca4  : qwerty
4.	5f4dcc3b5aa765d61d8327deb882cf99 : password
5.	96e79218965eb72c92a549dd5a330112 : 111111
6.	25d55ad283aa400af464c76d713c07ad : 12345678
7.	e99a18c428cb38d5f260853678922e03 : abc123
8.	fcea920f7412b5da7be0cf42b8c93759 : 1234567
9.	7c6a180b36896a0a8c02787eeafb0e4c : password1
10.	6c569aabbf7775ef8fc570e228c16b98: password!
11.	3f230640b78d7e71ac5514e57935eb69 : qazxsw
12.	917eb5e9d6d6bca820922a0c6f7cc28b: 	Pa$$word1
13.	f6a0cb102c62879d397b12b62c092c06 : bluered
14.	9b3b269ad0a208090309f091b3aba9db: Flamesbria2001
15.	16ced47d3fc931483e24933665cded6d : Oranolio1994
16.	1f5c5683982d7c3814d4d9e6d749b21e : spuffyffet
17.	8d763385e0476ae208f21bc63956f748 : moodie00
18.	defebde7b6ab6f24d5824682a16c3ae4 : nabox
19.	bdda5f03128bcbdfa78d8934529048cf : bandalls

HASHING ALGORITHM USED TILL 13th passwords: 

1.	e10adc3949ba59abbe56e057f20f883e : MD5
2.	25f9e794323b453885f5181f1b624d0b : MD5
3.	d8578edf8458ce06fbc5bb76a58c5ca4  : MD5
4.	5f4dcc3b5aa765d61d8327deb882cf99 : MD5
5.	96e79218965eb72c92a549dd5a330112 : MD5
6.	25d55ad283aa400af464c76d713c07ad : MD5
7.	e99a18c428cb38d5f260853678922e03 : MD5
8.	fcea920f7412b5da7be0cf42b8c93759 : MD5
9.	7c6a180b36896a0a8c02787eeafb0e4c : MD5
10.	6c569aabbf7775ef8fc570e228c16b98: MD5
11.	3f230640b78d7e71ac5514e57935eb69 : MD5
12.	917eb5e9d6d6bca820922a0c6f7cc28b: MD5
13.	f6a0cb102c62879d397b12b62c092c06 : MD5


