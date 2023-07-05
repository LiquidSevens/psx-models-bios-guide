# PSX Models & BIOS Guide

last updated 30th October 2018.

## Download
- **THERE ARE NO BIOS DOWNLOAD LINKS ON THIS PAGE**: This is simply a detailed list of every known PSX BIOS.
- [PSX BIOS DAT-file](https://github.com/LiquidDoubloon/psx-models-bios-guide/blob/master/Sony%20-%20PlayStation%20-%20BIOS%20Images%20(2018%2C%20Fixed).dat) (corrected, updated and fixed redump.org [DAT-file](http://redump.org/datfile/psx-bios/))

## Models Guide

- **DEVKITS**
    
    - **DTL-H2000** - is not a console, but a "developer board" - an addon developer inserts in his PC to write and debug PS games. it was, essentially, a PlayStation bundled in form of PC board with 8 MB instead of 2MB. only licensed developers had access to it. it was released _in January, 1994_, long before any retail PlayStation were released.
- **FIRST GENERATION**. motherboard PU-7. Rev. A of GPU, has S-Video
    
    - **SCPH-1000** 🇯🇵 - original Japanese console, _released on 03 December 1994_
    - **DTL-H1000** 🇯🇵 - Japanese blue-colored debugger. region lockup (for some odd reasons). all debuggers have the same 2MB RAM as regular consoles, information saying about having 8MB is wrong
    - **DTL-H1001** 🇺🇸 - North American blue-colored debugger. no regional lockup
    - **DTL-H1002** 🇬🇧 - European blue-colored debugger. no regional lockup
    - **DTL-H1000H** 🇯🇵 - same as DTL-H1000 but has gray-colored case and updated BIOS. used in display kiosk on events like E3 (they thought that using blue-colored debuggers on E3 will create false assumption that retail console will be of blue color, so they used gray-colored debugger to not confuse journalists and gamers)
    - **DTL-H1001H** 🇺🇸 - same as DTL-H1001 but has gray-colored case. display kiosk as above
    - **DTL-H1002H** ❓ - it is quite possible this console exist, but so far nobody have seen one. high chances that this console does not exist, because there were no major game convention in Europe
- **SECOND GENERATION**. motherboard PU-8. Rev. B of GPU (bug fixes in libraries), has no S-Video
    
    - **SCPH-3000** 🇯🇵 - Japanese version, _released on 21 July 1995_
    - **SCPH-1001** 🇺🇸 - original North American console, _released on 09 September 1995_. despite being named SCPH-1001, that console is based on SCPH-3000, not SCPH-1000, Sony used odd numeration here
    - **SCPH-1002** 🇬🇧 - original European console, _released on 29 September 1995_. again, based on SCPH-3000, not SCPH-1000
    - ~~**SCPH-1003**~~ ❗ - **DOES NOT EXIST**. there were rumors that Sony released PlayStation in Southeast Asian region alongside SCPH-1001 & SCPH-1002, but it is false. the very first console released in this region were SCPH-5003 / SCPH-5903 (gray import was available, though)
- **THIRD GENERATION**. motherboard PU-8. changes in CPU (on the part of GTE)
    
    - **SCPH-3500** 🇯🇵 - Japanese version, _released on 28 March 1996_
    - _2nd revision_ of **SCPH-1001** 🇺🇸 - Sony released updated versions of SCPH-1001 without altering the numeration. people sometimes referring it as SCPH-1001B to tell the difference from the second generation
    - _2nd revision_ of **SCPH-1002** 🇬🇧 - same as above, people referring it as SCPH-1002B
    - **DTL-H1100** 🇯🇵 - Japanese blue-colored debugger. it has a unique BIOS that is not available on any retail consoles.
    - **DTL-H1101** 🇺🇸 - North American blue-colored debugger
    - **DTL-H1102** 🇬🇧 - European blue-colored debugger
    - ~~**SCPH-2000**~~ ❗ - **DOES NOT EXIST**. some sites refer it as "all-region PS", but it is hoax, probably people confusing SCPH-2000 and DTL-H1000. "SCPH-2000" is, btw, the name of prototype adapter for never-released PlayStation keyboard. most probably, Sony thought about giving to console a Net-addon, but scrapped that idea
- **FOURTH GENERATION**. motherboard PU-8. Rev. C of GPU (GPU uses SGRAM now)
    
    - **SCPH-5000** 🇯🇵 - Japanese version, _released on 22 June 1996_
    - _3rd revision_ of **SCPH-1001** 🇺🇸 - Sony revised SCPH-1001 once again without changing the name. people refer it as SCPH-1001C
    - _3rd revision_ of **SCPH-1002** 🇬🇧 - same as above, people refering it as SCPH-1002C
    - **SCPH-5003** 🌏 - original Southeast Asian console. weirdly, the numeration follows SCPH-5000, but console features the SCPH-1001C's BIOS (in English). people assumed it did not exist, but it is mentioned in a manual for SCPH-103
    - **SCPH-5903** 🌏 - special Southeast Asian console with Video CD support. that version has separated japan-based BIOS
    - **DTL-H1200** 🇯🇵 - Japanese green-colored debugger
    - **DTL-H1201** 🇺🇸 - North American green-colored debugger
    - **DTL-H1202** 🇬🇧 - European green-colored debugger
    - **DTL-H3000** 🇯🇵 - Japanese black-colored Net Yaroze
    - **DTL-H3001** 🇺🇸 - North American black-colored Net Yaroze
    - **DTL-H3002** 🇬🇧 - European black-colored Net Yaroze
- **FIFTH GENERATION**. motherboard PU-18. relocation and improvements in CD-ROM drive. A/V direct out and RFU power connector removed. motherboard PCB reduced in size
    
    - **SCPH-5500** 🇯🇵 - Japanese version, _released on 15 November 1996_
    - **SCPH-5001** / **SCPH-5501** 🇺🇸 - North American SCPH-5500. they differ in supplies: SCPH-5001 has one controller, SCPH-5501 has two controllers and a memory card. for long time people thought that SCPH-5001 does not exist, but is mentioned in a manual to SCPH-101 (alongside SCPH-5501)
    - **SCPH-5502** / **SCPH-5552** 🇬🇧 - European SCPH-5500. same as above, differ in supplies. there is a false information that SCPH-5502 is a regular European console and SCPH-5552 is a rare promo-console for "Men in Black" movie. while it is true that "Men in Black"-based console PlayStation indeed was released - there also were the regular gray-colored versions of SCPH-5552
    - **SCPH-5503** 🌏 - Southeast Asian SCPH-5500
    - ~~**SCPH-5002**~~ ❗ - **DOES NOT EXIST**. it seems weird at first glance, because SCPH-5000 (Japanese fourth generation), SCPH-5001 (American fifth generation), SCPH-5003 (Southeast Asian fourth generation) do all exist, but not SCPH-5002, but it is fact. blame Sony for the confusing numeration. even if it would have existed it would be a third(!) European counterpart in fifth generation (together with SCPH-5502 and SCPH-5552) which is too much
- **SIXTH GENERATION**. motherboard PU-20. DualShock & Sound Scope support. different video encoder. CD circuits simplified. memory changed from 4 chips to 1
    
    - **SCPH-7000** 🇯🇵 - Japanese version, _released on 13 November 1997_
    - **SCPH-7001** 🇺🇸 - North American SCPH-7000
    - **SCPH-7002** 🇬🇧 - European SCPH-7000
    - **SCPH-7003** 🌏 - Southeast Asian SCPH-7000. oddly, but is has down-leveled BIOS against SCPH-7000 (3.0 instead of 4.0)
    - **SCPH-7000W** 🇯🇵 - the special Japanese blue-colored console, released to celebrate of 10 millionth sold unit. obviously, based on SCPH-7000, but has English BIOS and no regional lockup. known as "_Midnight Blue_"
- **SEVENTH GENERATION**. motherboard PU-22. reductions in electronics and hardware
    
    - **SCPH-7500** 🇯🇵 - Japanese version, _released on 01 December 1998_
    - **SCPH-7501** 🇺🇸 - North American SCPH-7500
    - **SCPH-7502** 🇬🇧 - European SCPH-7500
    - **SCPH-7503** 🌏 - Southeast Asian SCPH-7500. compare to SCPH-7003 it now has a modern BIOS
    - **SCPH-9903** 🇺🇸 - weird console released in North America. it is basically the SCPH-7501, but where an original console can operate on 120V only, the SCPH-9903 can handle 240V. sticker on the back says console was released in May 1999, but it still qualifies as seventh generation because of hardware
- **EIGHTH GENERATION**. motherboard PU-23. more motherboard reductions. removal of parallel I/O port
    
    - **SCPH-9000** 🇯🇵 - Japanese version, _released on 28 May 1999_
    - **SCPH-9001** 🇺🇸 - North American SCPH-9000
    - **SCPH-9002** 🇬🇧 - European SCPH-9000
    - **SCPH-9003** 🌏 - Southeast Asian SCPH-9000
- **NINTH GENERATION** (aka PSone). motherboard PM-41. the size of console was dramatically reduced. removal of serial port
    
    - **SCPH-100** 🇯🇵 - Japanese version, _released on 07 July 2000_
    - **SCPH-101** 🇺🇸 - North American SCPH-100, _released on 19 September 2000_
    - **SCPH-102** 🇬🇧 - European SCPH-100, _released on 29 September 2000_
    - _2nd revision_ of **SCPH-101** 🇺🇸 - Sony released the revised version of console without naming it differently - no hardware difference, just revamped BIOS
    - _2nd revision_ of **SCPH-102** 🇬🇧 - same as above
    - **SCPH-103** 🌏 - Southeast Asian SCPH-100. sources says it has better BIOS (4.6) than American analogue (4.4 / 4.5) - it is false, its BIOS matches 2nd revision of SCPH-102
    - **SCPH-102A** / **SCPH-102B** / **SCPH-102C** ❗ - people believe that there are three different versions of SCPH-102 differ on their hardware or BIOS. in fact all those versions differ in packages and supplies only: SCPH-102A has AV cable & AC adapter, SCPH-102B has RFU adapter & AC adapter, SCPH-102C has AV cable, AC adapter and Euro-Scart-adapter. Also manuals for SCPH-102A/SCPH-102B are English only, while SCPH-102C is present in six European languages

## BIOS Guide (short)

|BIOS date|redump.org name|consoles|CRC|MD5|
|---|---|---|---|---|
|1994-01-24 ❓|_ps-11_ (notPreserved)|**DTL-H2000**|18d0f7d8|2118230527a9f51bd9216e32fa912842|
|1994-09-22 🇯🇵|_ps-10j_|**SCPH-1000, DTL-H1000**|3b601fc8|239665b1a3dade1b5a52c06338011044|
|1995-01-22 🇯🇵|_ps-11j_|**SCPH-3000, DTL-H1000H**|3539def6|849515939161e62f6b866f6853006780|
|1995-05-07 🇺🇸|_ps-20a_|**SCPH-1001, DTL-H1001, DTL-H1001H**|55847d8c|dc2b9bf8da62ec93e868cfd29f0d067d|
|1995-05-10 🇬🇧|_ps-20e_|**SCPH-1002, DTL-H1002**|9bb87c4b|54847e693405ffeb0359c6287434cbef|
|1995-07-17 🇺🇸|_ps-21a_|**SCPH-1001, DTL-H1101**|aff00f2f|da27e8b6dab242d8f91a9b25d80c63b8|
|1995-07-17 🇬🇧|_ps-21e_|**SCPH-1002, DTL-H1102**|86c30531|417b34706319da7cf001e76e40136c23|
|1995-07-17 🇯🇵|_ps-21j_|**SCPH-3500**|bc190209|cba733ceeff5aef5c32254f1d617fa62|
|1995-12-04 🇺🇸|_ps-22a_|**SCPH-1001, SCPH-5003, DTL-H1201, DTL-H3001**|37157331|924e392ed05558ffdb115408c263dccf|
|1995-12-04 🇬🇧|_ps-22e_|**SCPH-1002, DTL-H1202, DTL-H3002**|1e26792f|e2110b8a2b97a8e0b857a45d32f7e187|
|1996-03-06 🇯🇵|_ps-22d_|**DTL-H1100**|decb22f5|ca5cfc321f916756e3f0effbfaeba13b|
|1995-12-04 🇯🇵|_ps-22j_|**SCPH-5000, DTL-H1200, DTL-H3000**|24fc7e17|57a06303dfa9cf9351222dfcbb4a29d9|
|1995-12-04 🇯🇵|_ps-22j(v)_|**SCPH-5903**|446ec5b2|81328b966e6dcf7ea1e32e55e1c104bb|
|1996-11-18 🇺🇸|_ps-30a_|**SCPH-5001, SCPH-5501, SCPH-5503, SCPH-7003**|8d8cb7e4|490f666e1afb15b7362b406ed1cea246|
|1997-01-06 🇬🇧|_ps-30e_|**SCPH-5502, SCPH-5552**|d786f0b9|32736f17079d0b2b7024407c39bd3050|
|1996-09-09 🇯🇵|_ps-30j_|**SCPH-5500**|ff3eeb8c|8dd7d5296a650fac7319bce665a6a53c|
|1997-08-18 🇯🇵|_ps-40j_|**SCPH-7000, SCPH-7500, SCPH-9000**|ec541cd0|8e4c14f567745eff2f0408c8129f72a6|
|1997-11-14 🇺🇸|_ps-41a(w)_|**SCPH-7000W**|b7c43dad|b84be139db3ee6cbd075630aa20a6553|
|1997-12-16 🇺🇸|_ps-41a_|**SCPH-7001, SCPH-7501, SCPH-7503, SCPH-9001, SCPH-9003, SCPH-9903**|502224b6|1e68c231d0896b7eadcad1d7d8e76129|
|1997-12-16 🇬🇧|_ps-41e_|**SCPH-7002, SCPH-7502, SCPH-9002**|318178bf|b9d9a0286c33dc6b7237bb13cd46fdee|
|2000-03-11 🇯🇵|_psone-43j_|**SCPH-100**|f2af798b|8abc1b549a4a80954addc48ef02c4521|
|2000-03-24 🇺🇸|_psone-44a_|**SCPH-101**|6a0e22a0|9a09ab7e49b422c007e6d54d7c49b965|
|2000-03-24 🇬🇧|_psone-44e_|**SCPH-102**|0bad7ea9|b10f5e0e3d9eb60e5159690680b1e774|
|2000-05-25 🇺🇸|_psone-45a_|**SCPH-101, SCPH-103**|171bdcec|6e3735ff4c7dc899ee98981385f6f3d0|
|2000-05-25 🇬🇧|_psone-45e_|**SCPH-102**|76b880e5|de93caec13d1a141a40a79f5c86168d6|
|2000-10-27 ❓|_ps2-50j_ (notPreserved)|**SCPH-18000**|0dcce9d7|d8f485717a5237285e4d7c5f881b7f32|

## BIOS Guide (long)

**(legend)**: **console names** - version, date | _redump.org name_ | CEX code | CRC , MD5

- **FIRST GENERATION**. motherboard PU-7
    
    - **SCPH-1000** 🇯🇵 - v10, 1994-09-22 | _ps-10j_ | CEX-1000 KT-3 by S.O. | 3b601fc8 , 239665b1a3dade1b5a52c06338011044
    - **DTL-H1000** 🇯🇵 - v10, 1994-09-22 | _ps-10j_ | CEX-1000 KT-3 by S.O. | 3b601fc8 , 239665b1a3dade1b5a52c06338011044
    - **DTL-H1001** 🇺🇸 - v20, 1995-05-07 | _ps-20a_ | CEX-1000 KT-3 by S.O. | 55847d8c , dc2b9bf8da62ec93e868cfd29f0d067d
    - **DTL-H1002** 🇬🇧 - v20, 1995-05-10 | _ps-20e_ | CEX-1000 KT-3 by S.O. | 9bb87c4b , 54847e693405ffeb0359c6287434cbef
    - **DTL-H1000H** 🇯🇵 - v11, 1995-01-22 | _ps-11j_ | CEX-1000 KT-3 by S.O. | 3539def6 , 849515939161e62f6b866f6853006780
    - **DTL-H1001H** 🇺🇸 - v20, 1995-05-07 | _ps-20a_ | CEX-1000 KT-3 by S.O. | 55847d8c , dc2b9bf8da62ec93e868cfd29f0d067d
- **SECOND GENERATION**. motherboard PU-8
    
    - **SCPH-3000** 🇯🇵 - v11, 1995-01-22 | _ps-11j_ | CEX-1000 KT-3 by S.O. | 3539def6 , 849515939161e62f6b866f6853006780
    - **SCPH-1001** 🇺🇸 - v20, 1995-05-07 | _ps-20a_ | CEX-1000 KT-3 by S.O. | 55847d8c , dc2b9bf8da62ec93e868cfd29f0d067d
    - **SCPH-1002** 🇬🇧 - v20, 1995-05-10 | _ps-20e_ | CEX-1000 KT-3 by S.O. | 9bb87c4b , 54847e693405ffeb0359c6287434cbef
- **THIRD GENERATION**. motherboard PU-8
    
    - **SCPH-3500** 🇯🇵 - v21, 1995-07-17 | _ps-21j_ | CEX-3000 KT-3 by K.S. | bc190209 , cba733ceeff5aef5c32254f1d617fa62
    - _2nd revision_ of **SCPH-1001** 🇺🇸 - v21, 1995-07-17 | _ps-21a_ | CEX-3000 KT-3 by K.S. | aff00f2f , da27e8b6dab242d8f91a9b25d80c63b8
    - _2nd revision_ of **SCPH-1002** 🇬🇧 - v21, 1995-07-17 | _ps-21e_ | CEX-3000 KT-3 by K.S. | 86c30531 , 417b34706319da7cf001e76e40136c23
    - **DTL-H1100** 🇯🇵 - v22, 1996-03-06 | _ps-22d_ | CEX-3000-1001-1002 by K.S. | decb22f5 , ca5cfc321f916756e3f0effbfaeba13b
    - **DTL-H1101** 🇺🇸 - v21, 1995-07-17 | _ps-21a_ | CEX-3000 KT-3 by K.S. | aff00f2f , da27e8b6dab242d8f91a9b25d80c63b8
    - **DTL-H1102** 🇬🇧 - v21, 1995-07-17 | _ps-21e_ | CEX-3000 KT-3 by K.S. | 86c30531 , 417b34706319da7cf001e76e40136c23
- **FOURTH GENERATION**. motherboard PU-8
    
    - **SCPH-5000** 🇯🇵 - v22, 1995-12-04 | _ps-22j_ | CEX-3000-1001-1002 by K.S. | 24fc7e17 , 57a06303dfa9cf9351222dfcbb4a29d9
    - _3rd revision_ of **SCPH-1001** 🇺🇸 - v22, 1995-12-04 | _ps-22a_ | CEX-3000-1001-1002 by K.S. | 37157331 , 924e392ed05558ffdb115408c263dccf
    - _3rd revision_ of **SCPH-1002** 🇬🇧 - v22, 1995-12-04 | _ps-22e_ | CEX-3000-1001-1002 by K.S. | 1e26792f , e2110b8a2b97a8e0b857a45d32f7e187
    - **SCPH-5003** 🌏 - v22, 1995-12-04 | _ps-22a_ | CEX-3000-1001-1002 by K.S. | 37157331 , 924e392ed05558ffdb115408c263dccf
    - **SCPH-5903** 🌏 - v22, 1995-12-04 | _ps-22j(v)_ | CEX-3000-1001-1002 by K.S. | 446ec5b2 , 81328b966e6dcf7ea1e32e55e1c104bb
    - **DTL-H1200** 🇯🇵 - v22, 1995-12-04 | _ps-22j_ | CEX-3000-1001-1002 by K.S. | 24fc7e17 , 57a06303dfa9cf9351222dfcbb4a29d9
    - **DTL-H1201** 🇺🇸 - v22, 1995-12-04 | _ps-22a_ | CEX-3000-1001-1002 by K.S. | 37157331 , 924e392ed05558ffdb115408c263dccf
    - **DTL-H1202** 🇬🇧 - v22, 1995-12-04 | _ps-22e_ | CEX-3000-1001-1002 by K.S. | 1e26792f , e2110b8a2b97a8e0b857a45d32f7e187
    - **DTL-H3000** 🇯🇵 - v22, 1995-12-04 | _ps-22j_ | CEX-3000-1001-1002 by K.S. | 24fc7e17 , 57a06303dfa9cf9351222dfcbb4a29d9
    - **DTL-H3001** 🇺🇸 - v22, 1995-12-04 | _ps-22a_ | CEX-3000-1001-1002 by K.S. | 37157331 , 924e392ed05558ffdb115408c263dccf
    - **DTL-H3002** 🇬🇧 - v22, 1995-12-04 | _ps-22e_ | CEX-3000-1001-1002 by K.S. | 1e26792f , e2110b8a2b97a8e0b857a45d32f7e187
- **FIFTH GENERATION**. motherboard PU-18
    
    - **SCPH-5500** 🇯🇵 - v30, 1996-09-09 | _ps-30j_ | CEX-3000-1001-1002 by K.S. | ff3eeb8c , 8dd7d5296a650fac7319bce665a6a53c
    - **SCPH-5001** / **SCPH-5501** 🇺🇸 - v30, 1996-11-18 | _ps-30a_ | CEX-3000-1001-1002 by K.S. | 8d8cb7e4 , 490f666e1afb15b7362b406ed1cea246
    - **SCPH-5502** / **SCPH-5552** 🇬🇧 - v30, 1997-01-06 | _ps-30e_ | CEX-3000-1001-1002 by K.S. | d786f0b9 , 32736f17079d0b2b7024407c39bd3050
    - **SCPH-5503** 🌏 - v30, 1996-11-18 | _ps-30a_ | CEX-3000-1001-1002 by K.S. | 8d8cb7e4 , 490f666e1afb15b7362b406ed1cea246
- **SIXTH GENERATION**. motherboard PU-20
    
    - **SCPH-7000** 🇯🇵 - v40, 1997-08-18 | _ps-40j_ | CEX-7000-7001 by K.S. | ec541cd0 , 8e4c14f567745eff2f0408c8129f72a6
    - **SCPH-7001** 🇺🇸 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
    - **SCPH-7002** 🇬🇧 - v41, 1997-12-16 | _ps-41e_ | CEX-3000-1001-1002 by K.S. | 318178bf , b9d9a0286c33dc6b7237bb13cd46fdee
    - **SCPH-7003** 🌏 - v30, 1996-11-18 | _ps-30a_ | CEX-3000-1001-1002 by K.S. | 8d8cb7e4 , 490f666e1afb15b7362b406ed1cea246
    - **SCPH-7000W** 🇯🇵 - v41, 1997-11-14 | _ps-41a(w)_ | CEX-3000-1001-1002 by K.S. | b7c43dad , b84be139db3ee6cbd075630aa20a6553
- **SEVENTH GENERATION**. motherboard PU-22
    
    - **SCPH-7500** 🇯🇵 - v40, 1997-08-18 | _ps-40j_ | CEX-7000-7001 by K.S. | ec541cd0 , 8e4c14f567745eff2f0408c8129f72a6
    - **SCPH-7501** 🇺🇸 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
    - **SCPH-7502** 🇬🇧 - v41, 1997-12-16 | _ps-41e_ | CEX-3000-1001-1002 by K.S. | 318178bf , b9d9a0286c33dc6b7237bb13cd46fdee
    - **SCPH-7503** 🌏 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
    - **SCPH-9903** 🇺🇸 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
- **EIGHTH GENERATION**. motherboard PU-23
    
    - **SCPH-9000** 🇯🇵 - v40, 1997-08-18 | _ps-40j_ | CEX-7000-7001 by K.S. | ec541cd0 , 8e4c14f567745eff2f0408c8129f72a6
    - **SCPH-9001** 🇺🇸 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
    - **SCPH-9002** 🇬🇧 - v41, 1997-12-16 | _ps-41e_ | CEX-3000-1001-1002 by K.S. | 318178bf , b9d9a0286c33dc6b7237bb13cd46fdee
    - **SCPH-9003** 🌏 - v41, 1997-12-16 | _ps-41a_ | CEX-3000-1001-1002 by K.S. | 502224b6 , 1e68c231d0896b7eadcad1d7d8e76129
- **NINTH GENERATION** (aka PSone)
    
    - **SCPH-100** 🇯🇵 - v43, 2000-03-11 | _psone-43j_ | CEX-3000-1001-1002 by K.S. | f2af798b , 8abc1b549a4a80954addc48ef02c4521
    - **SCPH-101** 🇺🇸 - v44, 2000-03-24 | _psone-44a_ | CEX-3000-1001-1002 by K.S. | 6a0e22a0 , 9a09ab7e49b422c007e6d54d7c49b965
    - **SCPH-102** 🇬🇧 - v44, 2000-03-24 | _psone-44e_ | CEX-3000-1001-1002 by K.S. | 0bad7ea9 , b10f5e0e3d9eb60e5159690680b1e774
    - _2nd revision_ of **SCPH-101** 🇺🇸 - v45, 2000-05-25 | _psone-45a_ | CEX-3000-1001-1002 by K.S. | 171bdcec , 6e3735ff4c7dc899ee98981385f6f3d0
    - _2nd revision_ of **SCPH-102** 🇬🇧 - v45, 2000-05-25 | _psone-45e_ | CEX-3000-1001-1002 by K.S. | 76b880e5 , de93caec13d1a141a40a79f5c86168d6
    - **SCPH-103** 🌏 - v45, 2000-05-25 | _psone-45a_ | CEX-3000-1001-1002 by K.S. | 171bdcec , 6e3735ff4c7dc899ee98981385f6f3d0
- **SPECIAL**
    
    - **DTL-H2000** - v11, 1994-01-24 | _not preserved_ | %no CEX code% | 18d0f7d8 , 2118230527a9f51bd9216e32fa912842
        - DTL-H2000 is a developer board for PC not a separate console, but it still has a BIOS. as for 2018-OCT-30, redump.org didn't preserve it
    - **Playstation 2** - v50, 2000-10-27 | _not preserved_ | PS compatible mode by M.T | 0dcce9d7 , d8f485717a5237285e4d7c5f881b7f32
        - Playstation 2 has a PSX emulation mode for backward compatibility and so it has a separate BIOS to run PSX games. as for 2018-OCT-30, redump.org didn't preserve it

## Bad BIOS dumps

|BIOS date|redump.org name|consoles|CRC|MD5|
|---|---|---|---|---|
|1995-05-07 🚫|_ps-20a_|**SCPH-1001, DTL-H1001**|75660aac|59071590099d21dd439896592338bf95|
|1995-12-04 🚫|_ps-22j_|**SCPH-5000, DTL-H1200, DTL-H3000**|826ac185|1eefa9775e3ac04000a4f81c922d96dc|
|1995-12-04 🚫|_ps-22j_|**SCPH-5000, DTL-H1200, DTL-H3000**|8c93a399|eb201d2d98251a598af467d4347bb62f|
|1997-01-06 🚫|_ps-30e_|**SCPH-5502, SCPH-5552**|4d9e7c86|e56ec1b027e2fe8a49217d9678f7f6bb|

## Changelog
- 2023-07-05: Salvaged original content by Tim Zaplatov. Rearranged sections and corrected minor errors. Otherwise, original data untouched save for irretrievable content.
- 2018-10-30: Last known commit by Tim Zaplatov.