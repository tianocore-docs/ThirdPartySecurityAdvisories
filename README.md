<!--- @file
  README.md for Third Party Security Advisories
  Copyright (c) 2022, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->

<img src="media/TianocoreTitlePageLogo.jpg" width="300" />

### {{ book.title }}

{% if book.draft %}
** DRAFT FOR REVIEW **
{% else %}
** {{ book.version }} **
{% endif %}

** {{ gitbook.time|date('MM/DD/YYYY hh:mm:ss') }} **

{% if book.udkrelease %}
** {{ book.udkrelease }} **
{% endif %}

This document will list briefings on each third party security issue found and give a description, a timeline on updating component, an acknowledgment that the solution is included in tagged release.

### TLDR;

|           CVE           |   Exposure  |  Recommended Stable Tags |
| ----------------------- | ----------- | ------------------------ |
| CVE-2021-3449 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2021-3450 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2021-3711 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2021-3712 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2021-4160 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2022-0778 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2022-1292 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2022-2068 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
| CVE-2022-2097 - OpenSSL | No cryptopkg Exposure | 1.1.1j, edk2-stable202105<BR> 1.1.1n, edk2-stable202205 |
|  |  |  |  |

### Process
_(short form)_

1. Security Bugs reported through: [National Vulnerability Database](https://nvd.nist.gov)
2. The issue is evaluated for EDK2 exposure
3. Determine Timeline for updating to Master
4. Update third party component list updated in version tag

### Revision History

| Revision   | Revision History   | Date        |
| ---------- | ------------------ | --------------- |
| .001.0       | Initial release.<BR> Logs 1 - 9  | Jul 20, 2022  |
| | | |