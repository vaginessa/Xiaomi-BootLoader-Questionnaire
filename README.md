# Xiaomi-BootLoader-Questionnaire  

https://github.com/MlgmXyysd/Xiaomi-BootLoader-Questionnaire  

#### Xiaomi BootLoader "Unlocking Qualification Test" update record



- Each ID is the internal ID of the Beehive questionnaire, which is used by users to write scripts.
- The answers are collected and organized and may not be completely correct. You are welcome to submit your answers.
- Options are sorted by ID from small to large. The order may change randomly during the actual answer.
- There are many word games, so pay attention to the details of the questions and options
- I wish each of you can sign in for 12 points every day, pass the application approval as soon as possible, and unlock the BootLoader
- Update reminder/correction left [Issues](https://github.com/MlgmXyysd/Xiaomi-BootLoader-Questionnaire/issues), discussion right [Discussions](https://github.com/MlgmXyysd/Xiaomi- BootLoader-Questionnaire/discussions)

## 2023.12.01

- Answer link: https://m.beehive.miui.com/Wc2BAFI5U3xqe_bYlNMT2g/
- Number of questions: 18
- Passing score: 93
- Time limit: 6 minutes, scores for answered questions will be calculated over time
- Note: Accounts that have already answered questions cannot answer questions again within 7 days.

<table>
	<tr align="center">
		<th rowspan="2">Question ID</td>
		<th rowspan="2">Question content</td>
		<th rowspan="2">Type</td>
		<th colspan="10">Options</td>
		<th rowspan="2">Answer</td>
	</tr>
	<tr align="center">
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
	</tr>
	<tr>
		<td>1482217</td>
		<td>How to output the anti-rollback mechanism (ANTI) version number in FASTBOOT mode</td>
		<td>Single choice question</td>
		<td>4862237</td>
		<td>fastboot -w ANTI</td>
		<td>4862238</td>
		<td>fastboot -r ANTI</td>
		<td>4862239</td>
		<td>fastboot getvar anti</td>
		<td>4862240</td>
		<td>fastboot devices</td>
		<td></td>
		<td></td>
		<td>4862239</td>
	</tr>
	<tr>
		<td>1481264</td>
		<td>Which of the following Bootloader lock statements is incorrect? </td>
		<td>Single choice question</td>
		<td>4859673</td>
		<td>Switching from the official version to the development version must be unlocked</td>
		<td>4859674</td>
		<td>You need to log in to your Xiaomi account when unlocking</td>
		<td>4859675</td>
		<td>Xiaomi account needs to be bound to the mobile phone</td>
		<td>4859676</td>
		<td>The system security factor will be reduced after unlocking</td>
		<td></td>
		<td></td>
		<td>4859673</td>
	</tr>
	<tr>
		<td>1481265</td>
		<td>Among the following flashing tools, which one is officially provided to users? </td>
		<td>Single choice question</td>
		<td>4859946</td>
		<td>91 Assistant</td>
		<td>4859677</td>
		<td>MiFlash</td>
		<td>4859678</td>
		<td>Flash Master</td>
		<td>4859679</td>
		<td>Online brush treasure</td>
		<td></td>
		<td></td>
		<td>4859677</td>
	</tr>
	<tr>
		<td>1481266</td>
		<td>How to flash twrp to the boot partition in the FASTBOOT command line? </td>
		<td>Single choice question</td>
		<td>4859680</td>
		<td>fastboot flash boot boot.img</td>
		<td>4859681</td>
		<td>fastboot flash recovery boot.img</td>
		<td>4859682</td>
		<td>fastboot flash update boot.img</td>
		<td>4859683</td>
		<td>fastboot flash update recovery boot.img</td>
		<td></td>
		<td></td>
		<td>4859680</td>
	</tr>
	<tr>
		<td>1481268</td>
		<td>How to burn img, bin, mbn, elf and other image file contents to a specified partition? </td>
		<td>Single choice question</td>
		<td>4859688</td>
		<td>fastboot getvar all <partition name></td>
		<td>4859689</td>
		<td>fastboot boot <kernel image file name or path> <partition name></td>
		<td>4859690</td>
		<td>fastboot flash <image path> <partition name></td>
		<td>4859691</td>
		<td>fastboot flash <Partition name> <Image file name or path></td>
		<td></td>
		<td></td>
		<td>4859691</td>
	</tr>
	<tr>
		<td>1481260</td>
		<td>Among the following statements about BL unlocking and rooting, which ones are correct</td>
		<td>Multiple choice questions</td>
		<td>4859659</td>
		<td>Flash third-party TWRP, usually choose to flash to the system partition</td>
		<td>4859660</td>
		<td>Flash into third-party recovery, data will usually not be lost</td>
		<td>4859661</td>
		<td>Erase cache partition data, personal data is usually not lost</td>
		<td>4859662</td>
		<td>On Xiaomi/Redmi phones, you can generally press and hold the volume down button and volume up button to enter Recovery</td>
		<td>4859752</td>
		<td>You should back up important data before online flashing</td>
		<td>4859660,4859661,4859752</td>
	</tr>
	<tr>
		<td>1481276</td>
		<td>The meaning of error 4004 when flashing MTK machine</td>
		<td>Single choice question</td>
		<td>4859723</td>
		<td>There is a huge gap between the ROM file and the mobile phone system</td>
		<td>4859722</td>
		<td>The flash software version does not match</td>
		<td>4859721</td>
		<td>Memory corruption</td>
		<td>4859720</td>
		<td>Driver problem</td>
		<td></td>
		<td></td>
		<td>4859720</td>
	</tr>
	<tr>
		<td>1481272</td>
		<td>There are some misconceptions about the role of FASTBOOT devices</td>
		<td>Multiple choice questions</td>
		<td>4859704</td>
		<td>List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859705</td>
		<td>List all devices that have entered Recovery mode and are connected to the PC normally</td>
		<td>4859706</td>
		<td>No response command detection</td>
		<td>4859707</td>
		<td>Check whether the phone has been updated</td>
		<td></td>
		<td></td>
		<td>4859705,4859706,4859707</td>
	</tr>
	<tr>
		<td>1481274</td>
		<td>The following statements about basic FASTBOOT commands are incorrect</td>
		<td>Multiple choice questions</td>
		<td>4859712</td>
		<td>fastboot getvar product: Output the internal code name of the model</td>
		<td>4859713</td>
		<td>fastboot oem device-info: Output all information about the device</td>
		<td>4859714</td>
		<td>fastboot erase <partition name>: clear all data in the phone</td>
		<td>4859715</td>
		<td>fastboot oem lock: enable BL lock protection</td>
		<td>4859985</td>
		<td>fastboot -w: List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859713,4859714,4859985</td>
	</tr>
	<tr>
		<td>1481275</td>
		<td>What scene problems can line brush be used to solve? </td>
		<td>Multiple choice questions</td>
		<td>4859716</td>
		<td>Want to downgrade back to the previous system version</td>
		<td>4859717</td>
		<td>Hope to completely delete data and protect privacy</td>
		<td>4859718</td>
		<td>The phone cannot be turned on but is unlocked</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td>4859716,4859717,4859718</td>
	</tr>
	<tr>
		<td>1481277</td>
		<td>What is the correct statement about JVM’s garbage collection mechanism</td>
		<td>Multiple choice questions</td>
		<td>4859724</td>
		<td>Serial Collector is suitable for situations with limited memory</td>
		<td>4859725</td>
		<td>CMS Collctor has a long recovery pause time in the Old area</td>
		<td>4859726</td>
		<td>Parallel Collector is inefficient</td>
		<td>4859727</td>
		<td>Serial Collector recycling speed is slow</td>
		<td></td>
		<td></td>
		<td>4859724,4859727</td>
	</tr>
	<tr>
		<td>1481270</td>
		<td>How to exit FASTBOOT mode? </td>
		<td>Multiple choice questions</td>
		<td>4859696</td>
		<td>In FASTBOOT mode, press and hold the power button for about 7-15 seconds to restart the system</td>
		<td>4859697</td>
		<td>Restart the system through "fastboot reboot" and "fastboot oem poweroff" commands or unplug and shut down</td>
		<td>4859698</td>
		<td>Some models will automatically restart or shut down within 5 minutes to half an hour if the data cable is not plugged in in FASTBOOT mode</td>
		<td>4859947</td>
		<td>Repeatedly plug and unplug the data cable 5 times</td>
		<td></td>
		<td></td>
		<td>4859696,4859697,4859698</td>
	</tr>
	<tr>
		<td>1481278</td>
		<td>What operations are the FASTBOOT mode usually used for? </td>
		<td>Multiple choice questions</td>
		<td>4859728</td>
		<td>Unlocking the bootloader</td>
		<td>4859729</td>
		<td>Update device drivers</td>
		<td>4859730</td>
		<td>Enable device wireless capabilities</td>
		<td>4859731</td>
		<td>Flash device firmware</td>
		<td>4859984</td>
		<td>Transfer large amounts of file data</td>
		<td>4859728,4859731</td>
	</tr>
	<tr>
		<td>1481279</td>
		<td>The system service in the Android system that is responsible for starting applications and managing the application life cycle is</td>
		<td>Single choice question</td>
		<td>4859732</td>
		<td>SystemManager</td>
		<td>4859733</td>
		<td>ApplicationManagerService</td>
		<td>4859734</td>
		<td>SystemServer</td>
		<td>4859735</td>
		<td>ActivityManagerService</td>
		<td></td>
		<td></td>
		<td>4859735</td>
	</tr>
	<tr>
		<td>1481367</td>
		<td>Which of the following commands can indirectly and visually check whether the device is connected normally? </td>
		<td>Single choice question</td>
		<td>4859980</td>
		<td>fastboot getvar all</td>
		<td>4859981</td>
		<td>fastboot getvar product</td>
		<td>4859982</td>
		<td>fastboot devices</td>
		<td>4859983</td>
		<td>fastboot getvar anti</td>
		<td></td>
		<td></td>
		<td>4859982</td>
	</tr>
	<tr>
		<td>1482215</td>
		<td>What are the types of FastBoot commands</td>
		<td>Multiple choice questions</td>
		<td>4862229</td>
		<td>Execution action class</td>
		<td>4862230</td>
		<td>Data backup class</td>
		<td>4862231</td>
		<td>Output information class</td>
		<td>4862232</td>
		<td>Erase data class</td>
		<td></td>
		<td></td>
		<td>4862229,4862231,4862232</td>
	</tr>
	<tr>
		<td>1482216</td>
		<td>Which of the following operations require unlocking the Bootloader lock? </td>
		<td>Multiple choice questions</td>
		<td>4862233</td>
		<td>Card swiping method to swipe the machine</td>
		<td>4862234</td>
		<td>FASTBOOT mode offline brushing</td>
		<td>4862235</td>
		<td>ROOT permissions</td>
		<td>4862236</td>
		<td>Wire Flash Development ROM</td>
		<td></td>
		<td></td>
		<td>4862234,4862235,4862236</td>
	</tr>
	<tr>
		<td>1481262</td>
		<td>Is there any incorrect statement about 9008 mode flashing? </td>
		<td>Multiple choice questions</td>
		<td>4859667</td>
		<td>The phone must be equipped with a Qualcomm or MediaTek processor to use 9008 mode flashing</td>
		<td>4859668</td>
		<td>The flashing opportunity in 9008 mode is more thorough than the flashing in fastboot mode</td>
		<td>4859669</td>
		<td>Only some Xiaomi phones can use 9008 mode</td>
		<td>4859941</td>
		<td>9008 mode can only be used when the mobile phone can enter the system normally</td>
		<td></td>
		<td></td>
		<td>4859941,4859667</td>
	</tr>
</table>

## 2023.11.30

- Answer link: https://m.beehive.miui.com/Wc2BAFI5U3xqe_bYlNMT2g/
- Number of questions: 18
- Passing score: 93
- Time limit (updated): 6 minutes, scores for answered questions will be calculated over time
- Note (update): Accounts that have already answered questions cannot answer questions again within 7 days.

<table>
	<tr align="center">
		<th rowspan="2">Question ID</td>
		<th rowspan="2">Question content</td>
		<th rowspan="2">Type</td>
		<th colspan="10">Options</td>
		<th rowspan="2">Answer</td>
	</tr>
	<tr align="center">
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
	</tr>
	<tr>
		<td>1481260</td>
		<td>Among the following statements about BL unlocking and rooting, which ones are correct</td>
		<td>Multiple choice questions</td>
		<td>4859659</td>
		<td>Flash third-party TWRP, usually choose to flash to the system partition</td>
		<td>4859660</td>
		<td>Flash into third-party recovery, data will usually not be lost</td>
		<td>4859661</td>
		<td>Erase cache partition data, personal data is usually not lost</td>
		<td>4859662</td>
		<td>On Xiaomi/Redmi phones, you can generally press and hold the power button and volume up button to enter Recovery</td>
		<td>4859752</td>
		<td>You should back up important data before online flashing</td>
		<td>4859660,4859661,4859662,4859752</td>
	</tr>
	<tr>
		<td>1481262</td>
		<td>Is there any correct statement about 9008 mode flashing? </td>
		<td>Multiple choice questions</td>
		<td>4859667</td>
		<td>The phone must be equipped with a Qualcomm processor to use 9008 mode flashing</td>
		<td>4859668</td>
		<td>The flashing opportunity in 9008 mode is more thorough than the flashing in fastboot mode</td>
		<td>4859669</td>
		<td>All Xiaomi phones can use 9008 mode</td>
		<td>4859941</td>
		<td>9008 mode can only be used when the mobile phone can enter the system normally</td>
		<td></td>
		<td></td>
		<td>4859667,4859668</td>
	</tr>
	<tr>
		<td>1481264</td>
		<td>Which of the following Bootloader lock statements is incorrect? </td>
		<td>Single choice question</td>
		<td>4859673</td>
		<td>Switching from the official version to the development version must be unlocked</td>
		<td>4859674</td>
		<td>You need to log in to your Xiaomi account when unlocking</td>
		<td>4859675</td>
		<td>Xiaomi account needs to be bound to the mobile phone</td>
		<td>4859676</td>
		<td>The system security factor will be reduced after unlocking</td>
		<td></td>
		<td></td>
		<td>4859673</td>
	</tr>
	<tr>
		<td>1481265</td>
		<td>Among the following flashing tools, which one is officially provided to users? </td>
		<td>Single choice question</td>
		<td>4859946</td>
		<td>91 Assistant</td>
		<td>4859677</td>
		<td>MiFlash</td>
		<td>4859678</td>
		<td>Flash Master</td>
		<td>4859679</td>
		<td>Online brush treasure</td>
		<td></td>
		<td></td>
		<td>4859677</td>
	</tr>
	<tr>
		<td>1481266</td>
		<td>How to flash twrp to the boot partition in the FASTBOOT command line? </td>
		<td>Single choice question</td>
		<td>4859680</td>
		<td>fastboot flash boot boot.img</td>
		<td>4859681</td>
		<td>fastboot flash recovery boot.img</td>
		<td>4859682</td>
		<td>fastboot flash update boot.img</td>
		<td>4859683</td>
		<td>fastboot flash update recovery boot.img</td>
		<td></td>
		<td></td>
		<td>4859680</td>
	</tr>
	<tr>
		<td>1481268</td>
		<td>How to burn img, bin, mbn, elf and other image file contents to a specified partition? </td>
		<td>Single choice question</td>
		<td>4859688</td>
		<td>fastboot getvar all <partition name></td>
		<td>4859689</td>
		<td>fastboot boot <kernel image file name or path> <partition name></td>
		<td>4859690</td>
		<td>fastboot flash <image path> <partition name></td>
		<td>4859691</td>
		<td>fastboot flash <Partition name> <Image file name or path></td>
		<td></td>
		<td></td>
		<td>4859691</td>
	</tr>
	<tr>
		<td>1481270</td>
		<td>How to exit FASTBOOT mode? </td>
		<td>Multiple choice questions</td>
		<td>4859696</td>
		<td>In FASTBOOT mode, press and hold the power button for about 7-15 seconds to restart the system</td>
		<td>4859697</td>
		<td>Restart the system through "fastboot reboot" and "fastboot oem poweroff" commands or unplug and shut down</td>
		<td>4859698</td>
		<td>Some models will automatically restart or shut down within 5 minutes to half an hour if the data cable is not plugged in in FASTBOOT mode</td>
		<td>4859947</td>
		<td>Repeatedly plug and unplug the data cable 5 times</td>
		<td></td>
		<td></td>
		<td>4859696,4859697,4859698</td>
	</tr>
	<tr>
		<td>1481272</td>
		<td>There are some misconceptions about the role of FASTBOOT devices</td>
		<td>Multiple choice questions</td>
		<td>4859704</td>
		<td>List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859705</td>
		<td>List all devices that have entered Recovery mode and are connected to the PC normally</td>
		<td>4859706</td>
		<td>No response command detection</td>
		<td>4859707</td>
		<td>Check whether the phone has been updated</td>
		<td></td>
		<td></td>
		<td>4859705,4859706,4859707</td>
	</tr>
	<tr>
		<td>1481274</td>
		<td>The following basic commands of FASTBOOT are correct</td>
		<td>Multiple choice questions</td>
		<td>4859712</td>
		<td>fastboot getvar product: Output the internal code name of the model</td>
		<td>4859713</td>
		<td>fastboot oem device-info: Output all information about the device</td>
		<td>4859714</td>
		<td>fastboot erase <partition name>: clear all data in the phone</td>
		<td>4859715</td>
		<td>fastboot oem lock: enable BL lock protection</td>
		<td>4859985</td>
		<td>fastboot -w: List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859712,4859715</td>
	</tr>
	<tr>
		<td>1481275</td>
		<td>What scene problems can line brush be used to solve? </td>
		<td>Multiple choice questions</td>
		<td>4859716</td>
		<td>Want to downgrade back to the previous system version</td>
		<td>4859717</td>
		<td>Hope to completely delete data and protect privacy</td>
		<td>4859718</td>
		<td>The phone cannot be turned on but is unlocked</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td>4859716,4859717,4859718</td>
	</tr>
	<tr>
		<td>1481276</td>
		<td>What does the FASTBOOT getvar all command do? </td>
		<td>Single choice question</td>
		<td>4859720</td>
		<td>Output all information about the device</td>
		<td>4859721</td>
		<td>Enter the mobile phone password of the device</td>
		<td>4859722</td>
		<td>Output the mobile phone number of the device</td>
		<td>4859723</td>
		<td>Output the updated version of the device</td>
		<td></td>
		<td></td>
		<td>4859720</td>
	</tr>
	<tr>
		<td>1481277</td>
		<td>What is the correct statement about JVM’s garbage collection mechanism</td>
		<td>Multiple choice questions</td>
		<td>4859724</td>
		<td>Serial Collector is suitable for situations with limited memory</td>
		<td>4859725</td>
		<td>CMS Collctor has a long recovery pause time in the Old area</td>
		<td>4859726</td>
		<td>Parallel Collector is highly efficient</td>
		<td>4859727</td>
		<td>Serial Collector has fast recycling speed</td>
		<td></td>
		<td></td>
		<td>4859724,4859726</td>
	</tr>
	<tr>
		<td>1481278</td>
		<td>What operations are the FASTBOOT mode usually used for? </td>
		<td>Multiple choice questions</td>
		<td>4859728</td>
		<td>Unlocking the bootloader</td>
		<td>4859729</td>
		<td>Update device drivers</td>
		<td>4859730</td>
		<td>Enable device wireless capabilities</td>
		<td>4859731</td>
		<td>Flash device firmware</td>
		<td>4859984</td>
		<td>Transfer large amounts of file data</td>
		<td>4859728,4859731</td>
	</tr>
	<tr>
		<td>1481279</td>
		<td>The system service in the Android system that is responsible for starting applications and managing the application life cycle is</td>
		<td>Single choice question</td>
		<td>4859732</td>
		<td>SystemManager</td>
		<td>4859733</td>
		<td>ApplicationManagerService</td>
		<td>4859734</td>
		<td>SystemServer</td>
		<td>4859735</td>
		<td>ActivityManagerService</td>
		<td></td>
		<td></td>
		<td>4859735</td>
	</tr>
	<tr>
		<td>1481367</td>
		<td>Which of the following commands can indirectly and visually check whether the device is connected normally? </td>
		<td>Single choice question</td>
		<td>4859980</td>
		<td>fastboot getvar all</td>
		<td>4859981</td>
		<td>fastboot getvar product</td>
		<td>4859982</td>
		<td>fastboot devices</td>
		<td>4859983</td>
		<td>fastboot getvar anti</td>
		<td></td>
		<td></td>
		<td>4859982</td>
	</tr>
	<tr>
		<td>1482215</td>
		<td>What are the types of FastBoot commands</td>
		<td>Multiple choice questions</td>
		<td>4862229</td>
		<td>Execution action class</td>
		<td>4862230</td>
		<td>Data backup class</td>
		<td>4862231</td>
		<td>Output information class</td>
		<td>4862232</td>
		<td>Erase data class</td>
		<td></td>
		<td></td>
		<td>4862229,4862231,4862232</td>
	</tr>
	<tr>
		<td>1482216</td>
		<td>Which of the following operations require unlocking the Bootloader lock? </td>
		<td>Multiple choice questions</td>
		<td>4862233</td>
		<td>Card swiping method to swipe the machine</td>
		<td>4862234</td>
		<td>FASTBOOT mode offline brushing</td>
		<td>4862235</td>
		<td>ROOT permissions</td>
		<td>4862236</td>
		<td>Wire Flash Development ROM</td>
		<td></td>
		<td></td>
		<td>4862234,4862235,4862236</td>
	</tr>
</table>

## 2023.11.29

- Answer link (updated): https://m.beehive.miui.com/Wc2BAFI5U3xqe_bYlNMT2g/
- Number of questions (updated): 18
- Passing score (updated): 93
- Time limit (update): 6 minutes
- Note (updated): Multiple-choice questions have been added, and the number of question options has been increased to a maximum of 5.

<table>
	<tr align="center">
		<th rowspan="2">Question ID</td>
		<th rowspan="2">Question content</td>
		<th rowspan="2">Type</td>
		<th colspan="10">Options</td>
		<th rowspan="2">Answer</td>
	</tr>
	<tr align="center">
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
	</tr>
	<tr>
		<td>1481260</td>
		<td>Among the following statements about BL unlocking and rooting, which ones are correct</td>
		<td>Multiple choice questions</td>
		<td>4859659</td>
		<td>Flash third-party TWRP, usually choose to flash to the system partition</td>
		<td>4859660</td>
		<td>Flash into third-party recovery, data will usually not be lost</td>
		<td>4859661</td>
		<td>Erase cache partition data, personal data is usually not lost</td>
		<td>4859662</td>
		<td>On Xiaomi/Redmi phones, you can generally press and hold the power button and volume down button to enter Recovery</td>
		<td>4859752</td>
		<td>You should back up important data before online flashing</td>
		<td>4859660,4859661,4859752</td>
	</tr>
	<tr>
		<td>1481262</td>
		<td>Is there any correct statement about 9008 mode flashing? </td>
		<td>Multiple choice questions</td>
		<td>4859667</td>
		<td>The phone must be equipped with a Qualcomm processor to use 9008 mode flashing</td>
		<td>4859668</td>
		<td>The flashing opportunity in 9008 mode is more thorough than the flashing in fastboot mode</td>
		<td>4859669</td>
		<td>All Xiaomi phones can use 9008 mode</td>
		<td>4859941</td>
		<td>9008 mode can only be used when the mobile phone can enter the system normally</td>
		<td></td>
		<td></td>
		<td>4859667,4859668</td>
	</tr>
	<tr>
		<td>1481264</td>
		<td>Which of the following Bootloader lock statements is incorrect? </td>
		<td>Single choice question</td>
		<td>4859673</td>
		<td>Switching from the official version to the development version must be unlocked</td>
		<td>4859674</td>
		<td>You need to log in to your Xiaomi account when unlocking</td>
		<td>4859675</td>
		<td>Xiaomi account needs to be bound to the mobile phone</td>
		<td>4859676</td>
		<td>The system security factor will be reduced after unlocking</td>
		<td></td>
		<td></td>
		<td>4859673</td>
	</tr>
	<tr>
		<td>1481265</td>
		<td>Among the following flashing tools, which one is officially provided to users? </td>
		<td>Single choice question</td>
		<td>4859946</td>
		<td>91 Assistant</td>
		<td>4859677</td>
		<td>MiFlash</td>
		<td>4859678</td>
		<td>Flash Master</td>
		<td>4859679</td>
		<td>Online brush treasure</td>
		<td></td>
		<td></td>
		<td>4859677</td>
	</tr>
	<tr>
		<td>1481266</td>
		<td>How to flash twrp to the boot partition in the FASTBOOT command line? </td>
		<td>Single choice question</td>
		<td>4859680</td>
		<td>fastboot flash boot boot.img</td>
		<td>4859681</td>
		<td>fastboot flash recovery boot.img</td>
		<td>4859682</td>
		<td>fastboot flash update boot.img</td>
		<td>4859683</td>
		<td>fastboot flash update recovery boot.img</td>
		<td></td>
		<td></td>
		<td>4859680</td>
	</tr>
	<tr>
		<td>1481268</td>
		<td>How to burn img, bin, mbn, elf and other image file contents to a specified partition? </td>
		<td>Single choice question</td>
		<td>4859688</td>
		<td>fastboot getvar all <partition name></td>
		<td>4859689</td>
		<td>fastboot boot <kernel image file name or path> <partition name></td>
		<td>4859690</td>
		<td>fastboot flash <image path> <partition name></td>
		<td>4859691</td>
		<td>fastboot flash <Partition name> <Image file name or path></td>
		<td></td>
		<td></td>
		<td>4859691</td>
	</tr>
	<tr>
		<td>1481270</td>
		<td>How to exit FASTBOOT mode? </td>
		<td>Multiple choice questions</td>
		<td>4859696</td>
		<td>In FASTBOOT mode, press and hold the volume button for about 7-15 seconds to restart the system</td>
		<td>4859697</td>
		<td>Restart the system through "fastboot reboot" and "fastboot oem poweroff" commands or unplug and shut down</td>
		<td>4859698</td>
		<td>Some models will automatically restart or shut down within 5 minutes to half an hour if the data cable is not plugged in in FASTBOOT mode</td>
		<td>4859947</td>
		<td>Repeatedly plug and unplug the data cable 5 times</td>
		<td></td>
		<td></td>
		<td>4859697,4859698</td>
	</tr>
	<tr>
		<td>1481272</td>
		<td>There are some misconceptions about the role of FASTBOOT devices</td>
		<td>Multiple choice questions</td>
		<td>4859704</td>
		<td>List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859705</td>
		<td>List all devices that have entered Recovery mode and are connected to the PC normally</td>
		<td>4859706</td>
		<td>No response command detection</td>
		<td>4859707</td>
		<td>Check whether the phone has been updated</td>
		<td></td>
		<td></td>
		<td>4859705,4859706,4859707</td>
	</tr>
	<tr>
		<td>1481274</td>
		<td>The following basic commands of FASTBOOT are correct</td>
		<td>Multiple choice questions</td>
		<td>4859712</td>
		<td>fastboot getvar product: Output the internal code name of the model</td>
		<td>4859713</td>
		<td>fastboot oem device-info: Output all information about the device</td>
		<td>4859714</td>
		<td>fastboot erase <partition name>: clear all data in the phone</td>
		<td>4859715</td>
		<td>fastboot oem lock: enable BL lock protection</td>
		<td>4859985</td>
		<td>fastboot -w: List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4859712,4859715</td>
	</tr>
	<tr>
		<td>1481275</td>
		<td>What scene problems can line brush be used to solve? </td>
		<td>Multiple choice questions</td>
		<td>4859716</td>
		<td>Want to downgrade back to the previous system version</td>
		<td>4859717</td>
		<td>Hope to completely delete data and protect privacy</td>
		<td>4859718</td>
		<td>The phone cannot be turned on but is unlocked</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td>4859716,4859717,4859718</td>
	</tr>
	<tr>
		<td>1481276</td>
		<td>What does the FASTBOOT getvar all command do? </td>
		<td>Single choice question</td>
		<td>4859720</td>
		<td>Output all information about the device</td>
		<td>4859721</td>
		<td>Enter the mobile phone password of the device</td>
		<td>4859722</td>
		<td>Output the mobile phone number of the device</td>
		<td>4859723</td>
		<td>Output the updated version of the device</td>
		<td></td>
		<td></td>
		<td>4859720</td>
	</tr>
	<tr>
		<td>1481277</td>
		<td>What is the correct statement about JVM’s garbage collection mechanism</td>
		<td>Multiple choice questions</td>
		<td>4859724</td>
		<td>Serial Collector is suitable for situations with limited memory</td>
		<td>4859725</td>
		<td>CMS Collctor has a long recovery pause time in the Old area</td>
		<td>4859726</td>
		<td>Parallel Collector is highly efficient</td>
		<td>4859727</td>
		<td>Serial Collector has fast recycling speed</td>
		<td></td>
		<td></td>
		<td>4859724,4859726</td>
	</tr>
	<tr>
		<td>1481278</td>
		<td>What operations are the FASTBOOT mode usually used for? </td>
		<td>Multiple choice questions</td>
		<td>4859728</td>
		<td>Unlocking the bootloader</td>
		<td>4859729</td>
		<td>Update device drivers</td>
		<td>4859730</td>
		<td>Enable device wireless capabilities</td>
		<td>4859731</td>
		<td>Flash device firmware</td>
		<td>4859984</td>
		<td>Transfer large amounts of file data</td>
		<td>4859728,4859731</td>
	</tr>
	<tr>
		<td>1481279</td>
		<td>The system service in the Android system that is responsible for starting applications and managing the application life cycle is</td>
		<td>Single choice question</td>
		<td>4859732</td>
		<td>SystemManager</td>
		<td>4859733</td>
		<td>ApplicationManagerService</td>
		<td>4859734</td>
		<td>SystemServer</td>
		<td>4859735</td>
		<td>ActivityManagerService</td>
		<td></td>
		<td></td>
		<td>4859735</td>
	</tr>
	<tr>
		<td>1481367</td>
		<td>Which of the following commands can indirectly and visually check whether the device is connected normally? </td>
		<td>Single choice question</td>
		<td>4859980</td>
		<td>fastboot getvar all</td>
		<td>4859981</td>
		<td>fastboot getvar product</td>
		<td>4859982</td>
		<td>fastboot devices</td>
		<td>4859983</td>
		<td>fastboot getvar anti</td>
		<td></td>
		<td></td>
		<td>4859982</td>
	</tr>
	<tr>
		<td>1482215</td>
		<td>What are the types of FastBoot commands</td>
		<td>Multiple choice questions</td>
		<td>4862229</td>
		<td>Execution action class</td>
		<td>4862230</td>
		<td>Data backup class</td>
		<td>4862231</td>
		<td>Output information class</td>
		<td>4862232</td>
		<td>Erase data class</td>
		<td></td>
		<td></td>
		<td>4862229,4862231,4862232</td>
	</tr>
	<tr>
		<td>1482216</td>
		<td>Which of the following operations require unlocking the Bootloader lock? </td>
		<td>Multiple choice questions</td>
		<td>4862233</td>
		<td>Card swiping method to swipe the machine</td>
		<td>4862234</td>
		<td>FASTBOOT mode offline brushing</td>
		<td>4862235</td>
		<td>ROOT permissions</td>
		<td>4862236</td>
		<td>Wire Flash Development ROM</td>
		<td></td>
		<td></td>
		<td>4862234,4862235,4862236</td>
	</tr>
	<tr>
		<td>1482217</td>
		<td>How to output the anti-rollback mechanism (ANTI) version number in FASTBOOT mode</td>
		<td>Single choice question</td>
		<td>4862237</td>
		<td>fastboot -w ANTI</td>
		<td>4862238</td>
		<td>fastboot -r ANTI</td>
		<td>4862239</td>
		<td>fastboot getvar anti</td>
		<td>4862240</td>
		<td>fastboot devices</td>
		<td></td>
		<td></td>
		<td>4862239</td>
	</tr>
</table>

## 2023.11.08

- Answer link: https://m.beehive.miui.com/jdXtFrvJLlOK1T2omVdcFQ/
- Number of questions: 25
- Passing score: 60
- Time limit: 10 minutes

<table>
	<tr align="center">
		<th rowspan="2">Question ID</td>
		<th rowspan="2">Question content</td>
		<th rowspan="2">Type</td>
		<th colspan="8">Options</td>
		<th rowspan="2">Answer</td>
	</tr>
	<tr align="center">
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
		<th>ID</td>
		<th>Content</td>
	</tr>
	<tr>
		<td>1461174</td>
		<td>How to unlock the bootloader of mobile phone? </td>
		<td>Single choice question</td>
		<td>4787594</td>
		<td>Enter MTK mode</td>
		<td>4787595</td>
		<td>Enter Recovery Mode</td>
		<td>4787596</td>
		<td>After applying for unlocking, download the tool to unlock</td>
		<td>4787597</td>
		<td>Unlock via Xiaomi Assistant</td>
		<td>4787596</td>
	</tr>
	<tr>
		<td>1461175</td>
		<td>How to save data and flash the machine? </td>
		<td>Single choice question</td>
		<td>4787598</td>
		<td>Backup data—Unlock Bootloader lock—Wire flash</td>
		<td>4787599</td>
		<td>Unlock Bootloader—Backup Data—Wire Flash</td>
		<td>4787600</td>
		<td>Unlock Bootloader - Wire Flash - Backup Data</td>
		<td>4787601</td>
		<td>Unlock Bootloader—Download ROM—Wire Flash</td>
		<td>4787598</td>
	</tr>
	<tr>
		<td>1461176</td>
		<td>Which of the following operations does not require unlocking the Bootloader lock? </td>
		<td>Single choice question</td>
		<td>4787602</td>
		<td>Card swiping method to swipe the machine</td>
		<td>4787603</td>
		<td>FASTBOOT mode offline brushing</td>
		<td>4787604</td>
		<td>Patch boot/init_boot to obtain root permissions</td>
		<td>4787605</td>
		<td>Wire Flash Development ROM</td>
		<td>4787602</td>
	</tr>
	<tr>
		<td>1461177</td>
		<td>What mode does wire brushing require the phone to enter? </td>
		<td>Single choice question</td>
		<td>4787606</td>
		<td>System update interface</td>
		<td>4787607</td>
		<td>FASTBOOT interface</td>
		<td>4787608</td>
		<td>Recovery interface</td>
		<td></td>
		<td></td>
		<td>4787607</td>
	</tr>
	<tr>
		<td>1461178</td>
		<td>How to enter FASTBOOT mode on Xiaomi mobile phone? </td>
		<td>Single choice question</td>
		<td>4787610</td>
		<td>Press and hold the volume + and volume - keys when the power is turned off</td>
		<td>4787611</td>
		<td>Press and hold the volume + key and power key when the power is turned off</td>
		<td>4787612</td>
		<td>Press and hold the volume-key and power key when the power is turned off</td>
		<td></td>
		<td></td>
		<td>4787612</td>
	</tr>
	<tr>
		<td>1461179</td>
		<td>Which of the following Bootloader lock statements is incorrect? </td>
		<td>Single choice question</td>
		<td>4787614</td>
		<td>Switching from the official version to the development version must be unlocked</td>
		<td>4787615</td>
		<td>You need to log in to your Xiaomi account when unlocking</td>
		<td>4787616</td>
		<td>Xiaomi account needs to be bound to the mobile phone</td>
		<td>4787617</td>
		<td>The system security factor will be reduced after unlocking</td>
		<td>4787614</td>
	</tr>
	<tr>
		<td>1461180</td>
		<td>Among the following flashing tools, which one is officially provided to users? </td>
		<td>Single choice question</td>
		<td>4787618</td>
		<td>MiFlash</td>
		<td>4787619</td>
		<td>Flash Master</td>
		<td>4787620</td>
		<td>Online brush treasure</td>
		<td></td>
		<td></td>
		<td>4787618</td>
	</tr>
	<tr>
		<td>1461181</td>
		<td>How to flash twrp to the boot partition in the FASTBOOT command line? </td>
		<td>Single choice question</td>
		<td>4787622</td>
		<td>fastboot flash boot boot.img</td>
		<td>4787623</td>
		<td>fastboot flash recovery boot.img</td>
		<td>4787624</td>
		<td>fastboot flash update boot.img</td>
		<td>4787625</td>
		<td>fastboot flash update recovery boot.img</td>
		<td>4787622</td>
	</tr>
	<tr>
		<td>1461182</td>
		<td>How to output the anti-rollback mechanism (ANTI) version number in FASTBOOT mode</td>
		<td>Single choice question</td>
		<td>4787626</td>
		<td>fastboot -w ANTI</td>
		<td>4787627</td>
		<td>fastboot -r ANTI</td>
		<td>4787628</td>
		<td>fastboot getvar anti</td>
		<td>4787948</td>
		<td>fastboot devices</td>
		<td>4787628</td>
	</tr>
	<tr>
		<td>1461183</td>
		<td>How to burn img, bin, mbn, elf and other image file contents to a specified partition? </td>
		<td>Single choice question</td>
		<td>4787629</td>
		<td>fastboot getvar anti<Image file name or path></td>
		<td>4787630</td>
		<td>fastboot getvar anti<Image file name and path></td>
		<td>4787631</td>
		<td>fastboot flash <image path> <file name></td>
		<td>4787632</td>
		<td>fastboot flash <Partition name> <Image file name or path></td>
		<td>4787632</td>
	</tr>
	<tr>
		<td>1461184</td>
		<td>In FASTBOOT mode, how does the phone connect to the computer? </td>
		<td>Single choice question</td>
		<td>4787633</td>
		<td>USB connection</td>
		<td>4787634</td>
		<td>Wireless connection</td>
		<td>4787635</td>
		<td>Bluetooth connection</td>
		<td>4787636</td>
		<td>Ethernet connection</td>
		<td>4787633</td>
	</tr>
	<tr>
		<td>1461185</td>
		<td>How to exit FASTBOOT mode? </td>
		<td>Single choice question</td>
		<td>4787637</td>
		<td>In FASTBOOT mode, press and hold the power button for about 7-15 seconds to restart the system</td>
		<td>4787638</td>
		<td>Restart the system through "fastboot reboot" and "fastboot oem poweroff" commands or unplug and shut down</td>
		<td>4787639</td>
		<td>Some models will automatically restart or shut down within 5 minutes to half an hour if the data cable is not plugged in in FASTBOOT mode</td>
		<td>4787640</td>
		<td>All are correct</td>
		<td>4787640</td>
	</tr>
	<tr>
		<td>1461186</td>
		<td>What categories can FASTBOOT commands be roughly divided into? </td>
		<td>Single choice question</td>
		<td>4787641</td>
		<td>Output information class</td>
		<td>4787642</td>
		<td>Execution action class</td>
		<td>4787643</td>
		<td>Erase data class</td>
		<td>4787644</td>
		<td>All are correct</td>
		<td>4787644</td>
	</tr>
	<tr>
		<td>1461187</td>
		<td>What do FASTBOOT devices do? </td>
		<td>Single choice question</td>
		<td>4787645</td>
		<td>List all devices that have entered FASTBOOT mode and are connected to the PC normally</td>
		<td>4787646</td>
		<td>List all devices that have entered Recovery mode and are connected to the PC normally</td>
		<td>4787647</td>
		<td>No response command detection</td>
		<td>4787648</td>
		<td>Check whether the phone has been updated</td>
		<td>4787645</td>
	</tr>
	<tr>
		<td>1461188</td>
		<td>How to check whether the connected device is connected normally? </td>
		<td>Single choice question</td>
		<td>4787649</td>
		<td>fastboot getvar all</td>
		<td>4787650</td>
		<td>fastboot getvar product</td>
		<td>4787651</td>
		<td>fastboot devices</td>
		<td>4787652</td>
		<td>fastboot getvar anti</td>
		<td>4787651</td>
	</tr>
	<tr>
		<td>1461189</td>
		<td>What operation does the flag "-w" used in the FASTBOOT command represent? </td>
		<td>Single choice question</td>
		<td>4787653</td>
		<td>Restart your phone</td>
		<td>4787654</td>
		<td>Download the latest complete package</td>
		<td>4787655</td>
		<td>Update system</td>
		<td>4787656</td>
		<td>Clear all data</td>
		<td>4787656</td>
	</tr>
	<tr>
		<td>1461190</td>
		<td>What scene problems are used to solve line brushing? </td>
		<td>Single choice question</td>
		<td>4787657</td>
		<td>Want to downgrade back to the previous system version</td>
		<td>4787658</td>
		<td>Hope to completely delete data and protect privacy</td>
		<td>4787659</td>
		<td>The phone cannot be turned on but is unlocked</td>
		<td>4787660</td>
		<td>All are correct</td>
		<td>4787660</td>
	</tr>
	<tr>
		<td>1461191</td>
		<td>What does the FASTBOOT getvar all command do? </td>
		<td>Single choice question</td>
		<td>4787661</td>
		<td>Output all information about the device</td>
		<td>4787662</td>
		<td>Enter the mobile phone password of the device</td>
		<td>4787663</td>
		<td>Output the mobile phone number of the device</td>
		<td>4787664</td>
		<td>Output the updated version of the device</td>
		<td>4787661</td>
	</tr>
	<tr>
		<td>1461192</td>
		<td>What is the command used to flash firmware in FASTBOOT mode? </td>
		<td>Single choice question</td>
		<td>4787665</td>
		<td>load</td>
		<td>4787666</td>
		<td>run</td>
		<td>4787667</td>
		<td>boot</td>
		<td>4787668</td>
		<td>flash</td>
		<td>4787668</td>
	</tr>
	<tr>
		<td>1461193</td>
		<td>What operations are the FASTBOOT mode usually used for? </td>
		<td>Single choice question</td>
		<td>4787669</td>
		<td>Transfer large files</td>
		<td>4787670</td>
		<td>Update device drivers</td>
		<td>4787671</td>
		<td>Enable device wireless capabilities</td>
		<td>4787672</td>
		<td>Flash device firmware, unlock bootloader</td>
		<td>4787672</td>
	</tr>
	<tr>
		<td>1461194</td>
		<td>What is the difference between FASTBOOT mode and Recovery mode? </td>
		<td>Single choice question</td>
		<td>4787673</td>
		<td>Recovery can directly enter safe mode</td>
		<td>4787674</td>
		<td>FASTBOOT mode refers to "line brushing"</td>
		<td>4787675</td>
		<td>Recovery mode refers to "card swiping"</td>
		<td>4787676</td>
		<td>All are correct</td>
		<td>4787676</td>
	</tr>
	<tr>
		<td>1461195</td>
		<td>What does it mean to delete all in MiFlash? </td>
		<td>Single choice question</td>
		<td>4787678</td>
		<td>Delete Xiaomi cloud service data</td>
		<td>4787679</td>
		<td>Delete all data in Xiaomi shopping cart</td>
		<td>4787677</td>
		<td>Delete all data including Data</td>
		<td>4787680</td>
		<td>Delete Mijia connected devices</td>
		<td>4787677</td>
	</tr>
	<tr>
		<td>1461196</td>
		<td>What does it look like after entering FASTBOOT mode? </td>
		<td>Single choice question</td>
		<td>4787681</td>
		<td>Xiaomi is displayed on the screen</td>
		<td>4787683</td>
		<td>Redmi is displayed on the screen</td>
		<td>4787684</td>
		<td>English FASTBOOT is displayed on the screen</td>
		<td></td>
		<td></td>
		<td>4787684</td>
	</tr>
	<tr>
		<td>1461197</td>
		<td>What does it mean if a mobile phone can only enter FASTBOOT? </td>
		<td>Single choice question</td>
		<td>4787685</td>
		<td>The system may be damaged</td>
		<td>4787687</td>
		<td>Bootloader damaged</td>
		<td>4787688</td>
		<td>All are correct</td>
		<td></td>
		<td></td>
		<td>4787688</td>
	</tr>
	<tr>
		<td>1461198</td>
		<td>Can the Bootloader lock be unlocked if it is unlocked? </td>
		<td>Single choice question</td>
		<td>4787689</td>
		<td>Can</td>
		<td>4787690</td>
		<td>Cannot</td>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
		<td>4787689</td>
	</tr>
</table>
