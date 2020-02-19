# Study_pdf

这里是我学习Windows内核上参阅过的感觉对自己有用的一些资料，大多是Windows平台上搜集的一些paper，fuzz的话我会逐渐补上，当然是我自己看完了然后觉得有用的才会放上来

## Principle

* 内存池分配机制

  | Year | PDF                                                          | Content                     |
  | ---- | ------------------------------------------------------------ | --------------------------- |
  | 2011 | [BlackHat_DC_2011_Mandt_kernelpool-wp](https://github.com/ThunderJie/Study_pdf/blob/master/BlackHat_DC_2011_Mandt_kernelpool-wp.pdf) | Windows 7平台内存池分配原理 |

* Windows kernel提权原理

  | Year | PDF                                                          | Content             |
  | ---- | ------------------------------------------------------------ | ------------------- |
  | 2012 | [BH_US_12_Cerrudo_Windows_Kernel_WP](https://github.com/ThunderJie/Study_pdf/blob/master/BH_US_12_Cerrudo_Windows_Kernel_WP.pdf) | Windows令牌提权原理 |

* Bypass

  | Year | PDF                                                          | Content        |
  | ---- | ------------------------------------------------------------ | -------------- |
  | 2015 | [Windows SMEP bypass U=S](https://github.com/ThunderJie/Study_pdf/blob/master/Windows%20SMEP%20bypass%20U%3DS.pptx) | SMEP原理及绕过 |

## Exploit & Trick

* 任意读写技巧

  | Year | PDF                                                          | Content                      |
  | ---- | ------------------------------------------------------------ | ---------------------------- |
  | 2015 | [Abusing GDI for ring0 exploit primitives]([https://github.com/ThunderJie/Study_pdf/blob/master/Abusing%20GDI%20for%20ring0%20exploit%20primitives-2015.pdf](https://github.com/ThunderJie/Study_pdf/blob/master/Abusing GDI for ring0 exploit primitives-2015.pdf)) | 滥用Bitmap实现任意读写       |
  | 2017 | [Abusing_GDI_for_ring0_exploit_primitives_Evolution_Slides](https://github.com/ThunderJie/Study_pdf/blob/master/Abusing_GDI_for_ring0_exploit_primitives_Evolution_Slides.pdf) | 滥用其他GDI对象实现任意读写  |
  | 2017 | [us-17-Schenk-Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level–Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp](https://github.com/ThunderJie/Study_pdf/blob/master/us-17-Schenk-Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level%E2%80%93Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp.pdf) | Windows 10上任意读写技巧分析 |
  | 2017 | [Windows 10 内核漏洞利用防护及其绕过方法](https://github.com/ThunderJie/Study_pdf/blob/master/Windows%2010%20%E5%86%85%E6%A0%B8%E6%BC%8F%E6%B4%9E%E5%88%A9%E7%94%A8%E9%98%B2%E6%8A%A4%E5%8F%8A%E5%85%B6%E7%BB%95%E8%BF%87%E6%96%B9%E6%B3%95.pdf) | 上一个paper的中文翻译版本    |

* CVE-2016-7255

  | Year | PDF                                                          | Content                         |
  | ---- | ------------------------------------------------------------ | ------------------------------- |
  | 2017 | [mwri-securitay-2017-samdb-a-window-into-ring0](https://github.com/ThunderJie/Study_pdf/blob/master/mwri-securitay-2017-samdb-a-window-into-ring0.pdf) | 从攻击面引入到CVE-2016-7255分析 |

