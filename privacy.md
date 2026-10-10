# Basin Privacy Policy

Effective date: October 10, 2026

Basin is a voice memo app that turns what you say into text on your iPhone, with an app for Apple Watch and, with Basin Pro, an app for Mac. This policy explains what happens to your information when you use it. The short version: Basin does not collect any data. Your recordings stay on your iPhone (a recording made on Apple Watch is moved to your paired iPhone) and are never synced. If you buy Basin Pro and keep iCloud Sync on, the text of your memos is also kept in your own private iCloud database so that it appears on your other devices; we (the developer) cannot access it.

## We collect no data

Basin has no account, no sign-in and no server of its own. We do not collect, receive, store or sell any information about you or about how you use the app. Basin contains no analytics, no advertising and no tracking, and it includes no third-party software development kits. This is the same for the free app and for Basin Pro, on iPhone, Apple Watch and Mac.

## Where your memos are stored

Your recordings, transcripts, summaries, titles, threads, links and settings are stored on your device, inside Basin's own storage. Basin never uploads them to us.

- Without Basin Pro, or with iCloud Sync turned off, everything stays on the device.
- With Basin Pro and iCloud Sync on, the text of your memos also syncs through your iCloud account (see "iCloud Sync (Basin Pro)" below).
- Recordings never sync. Audio stays on the iPhone that recorded it; a recording made with Basin on Apple Watch is sent directly to your paired iPhone and removed from the watch once it has arrived, and from then on it stays on that iPhone.
- Settings stay on each device and are not synced.

If you delete a memo, it stays in Recently Deleted for 30 days and is then removed. Deleting the app from an iPhone or Apple Watch removes all of its data from that device. On a Mac, moving Basin to the Trash leaves its data in its container folder (~/Library/Containers/com.yoon.CatchIdea) until you delete that folder. Like other app data, Basin's data is part of your device backups (for example iCloud Backup) if you have backups turned on; those backups are made and managed by Apple under your own account, not by us.

## iCloud Sync (Basin Pro)

If you buy Basin Pro, Basin keeps your memos' text the same on your iPhones and Macs that are signed in to the same Apple Account.

- What syncs: titles, transcripts (with their formatting) and the original transcript Basin keeps of each memo, summaries, dates, favorites and pins, threads, links between memos, which memos are in Recently Deleted, your replacement rules, details such as each memo's language, and the file name and length of each recording, but not the recording itself. When a recording is deleted for good, a note with its file name and the time it was deleted is kept, so your other devices delete their copy too.
- Where it goes: your private database in iCloud (Apple's CloudKit service), in Basin's container. It is tied to your Apple Account. We cannot see, open or download it, and no Basin server is involved. Apple stores this data under its own terms and privacy policy, and it is encrypted in transit and on Apple's servers.
- When it starts: the next time you open Basin after buying Basin Pro. You can turn it off on each device in Settings › iCloud Sync (on the Mac: Basin › Settings); the change takes effect the next time you open Basin.
- When sync is off, or if Basin Pro is refunded or a Basin Pro subscription ends, that device stops syncing. No memo is deleted from the device, and what is already in your iCloud stays there.
- Deleting with sync on: moving a memo to Recently Deleted, restoring it, or deleting it permanently on one device does the same on your other synced devices and in iCloud. When a memo is permanently deleted on any device, the device that holds its recording deletes the recording as well — right away if the memo was deleted there, otherwise a week after the deletion. A recording added on another device before that change reached it can stay on that device.
- Removing your memos from iCloud: while iCloud Sync is on, permanently delete a memo on your iPhone (in Recently Deleted, swipe left on the memo and tap the trash button) and it is removed from iCloud and from your other synced devices (only the note with its recordings' file names and the time of deletion stays); memos left in Recently Deleted are removed the same way after 30 days. Turning sync off, a refund, the end of a subscription or deleting the app does not remove what is already in iCloud. You can also remove all of Basin's data from iCloud, with or without Basin Pro, in your iCloud storage settings (Manage Storage). This does not delete the memos on your devices, and a device that still has iCloud Sync on uploads its memos again, so first turn off iCloud Sync in Basin on each device and open Basin again there.
- To notice when the iCloud account on a device changes, Basin keeps on the device a token that the system provides for the signed-in account. It never leaves the device and does not identify you to us.
- iCloud can briefly wake Basin in the background when something changed on your other devices. Basin then brings in those changes and does the same on-device upkeep it does when you open it (for example widgets, search and, if you set it up, automatic export to your folder); it never records at such times.

## Local safety copies

On each device where iCloud Sync is on, Basin keeps a few copies of its memo store inside its own storage on that device: the copy made just before the device first synced, and the five most recent later copies, at most one every six hours. No copy is made when the device is low on storage. They hold the text and details of your memos, not recordings. They exist so that memos can be brought back if something goes wrong with sync (on iPhone: Settings › Restore Memos from a Local Copy). Basin never uploads them. They are removed together with the rest of Basin's data on that device (see "Where your memos are stored"), and, like other app data, they are part of your device backups if you have backups turned on.

## Basin for Mac (Basin Pro)

Basin for Mac shows the memos that iCloud Sync brings from your iPhone. On the Mac you can read, search, copy and export memos, rename them, and move them to Recently Deleted or restore them from there; these changes sync back to your other devices. Basin for Mac does not record, transcribe, play audio or create summaries, and it does not use the microphone. It keeps its memos, its settings and the local safety copies described above in its own sandboxed storage on the Mac.

## Basin Pro purchase

Basin Pro is an in-app purchase: a monthly or 3-month auto-renewing subscription, or a one-time lifetime purchase. Apple handles the purchase, renewals and cancellations through the App Store; we never see your payment details, your name or your Apple Account. You manage or cancel a subscription in your Apple Account settings. Basin asks Apple's StoreKit on your device whether your Apple Account has Basin Pro (an active subscription or the lifetime purchase) and whether it can still get the first free month, and remembers whether you have Basin Pro on the device, so Basin Pro also works offline. Like every developer, we see the App Store's sales reports from Apple, which do not include your name, contact details or Apple Account.

Not buying Basin Pro, getting a refund or the end of a subscription never deletes a memo. A refund or the end of a subscription stops iCloud Sync, automatic export and the other Basin Pro features. On a Mac, the memos already there stay and can still be read and copied.

## Transcription and summaries happen on your device

- Speech is transcribed on your device with Apple's Speech framework. The first time you record in a language, iOS may download Apple's speech recognition model for that language. That download is handled by iOS and does not include your recordings or text.
- Summaries and suggested titles are created on your device with Apple Intelligence (Apple's on-device Foundation Models), on devices that support it.
- Suggestions of related memos are calculated on your device.
- Basin for Mac does none of this; it shows the results your iPhone made.

## No transfer to third parties

Basin does not send your recordings or text to us or to any third party. Apart from iCloud Sync, which comes with Basin Pro and keeps your memo text in your own iCloud, information leaves your device only when you choose to share or export it — for example, when you share a memo's text, image or audio file, open a memo in Obsidian, post it to X, create a reminder in Apple's Reminders app, or export memos as Markdown files to a folder you picked (including automatic export with Basin Pro). In those cases the information goes to the app, service or folder you picked, and that app's or service's own privacy policy applies. If you pick a folder that a cloud service keeps in sync, that service's policy applies to the exported files.

## Permissions

- Microphone (iPhone and Apple Watch): used only to record your voice memos.
- Reminders: requested only when you create a reminder from a memo, and used only to create or show that reminder.
- Folders (Basin Pro, iPhone and Mac): Basin can write only to a folder you pick for export. It remembers that folder on the device so that automatic export can keep writing Markdown files of your memos there. You can pick another folder or turn automatic export off in Settings › Advanced Export.
- iCloud (Basin Pro): Basin uses the iCloud account signed in on the device; it never asks for your password.

You can turn microphone and Reminders access off at any time in the Settings app, stop folder writes by turning off Automatic export in Basin's Settings › Advanced Export, and turn iCloud off for Basin in your Apple Account's iCloud settings.

## Children

Basin does not collect personal information from anyone, including children.

## Changes to this policy

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions about this policy: i7434554@gmail.com

---

# Basin 개인정보 처리방침

시행일: 2026년 10월 10일

Basin은 말한 내용을 iPhone에서 글로 바꿔 주는 음성 메모 앱입니다. Apple Watch 앱이 있고, Basin Pro를 구입하면 Mac 앱도 쓸 수 있습니다. 이 방침은 Basin을 사용할 때 정보가 어떻게 다뤄지는지 설명합니다. 요약하면, Basin은 어떤 데이터도 수집하지 않습니다. 녹음은 iPhone에만 남고(Apple Watch에서 한 녹음은 연결된 iPhone으로 옮겨집니다) 동기화되지 않습니다. Basin Pro를 구입하고 iCloud 동기화를 켜 두면 메모의 글이 다른 기기에도 보이도록 사용자 본인의 iCloud 개인 데이터베이스에도 보관되며, 개발자는 여기에 접근할 수 없습니다.

## 수집하는 데이터 없음

Basin에는 계정도, 로그인도, 자체 서버도 없습니다. 개발자는 사용자나 사용자의 앱 사용 방식에 관한 어떤 정보도 수집하거나 받거나 저장하거나 판매하지 않습니다. 분석 도구, 광고, 추적이 없고, 서드파티 소프트웨어 개발 키트(SDK)도 넣지 않았습니다. 무료 앱이든 Basin Pro든, iPhone·Apple Watch·Mac 어디서든 마찬가지입니다.

## 메모가 저장되는 곳

녹음, 받아쓴 글, 요약, 제목, 폴더, 연결, 설정은 기기 안의 Basin 전용 저장 공간에 저장됩니다. Basin은 이것을 개발자에게 올려 보내지 않습니다.

- Basin Pro가 없거나 iCloud 동기화를 끈 경우, 모든 것이 기기 안에만 있습니다.
- Basin Pro를 구입하고 iCloud 동기화를 켠 경우, 메모의 글이 사용자의 iCloud 계정을 통해서도 동기화됩니다(아래 "iCloud 동기화(Basin Pro)" 참조).
- 녹음은 동기화되지 않습니다. 오디오는 녹음한 iPhone에만 남습니다. Apple Watch의 Basin으로 녹음하면 녹음은 연결된 iPhone으로 바로 보내지고, 도착하면 워치에서 지워집니다. 그 뒤로는 그 iPhone에만 남습니다.
- 설정은 기기마다 따로 저장되며 동기화되지 않습니다.

메모를 지우면 30일 동안 최근 삭제된 항목에 있다가 삭제됩니다. iPhone이나 Apple Watch에서 앱을 지우면 그 기기에서 앱의 모든 데이터가 지워집니다. Mac에서는 Basin을 휴지통으로 옮겨도 데이터가 컨테이너 폴더(~/Library/Containers/com.yoon.CatchIdea)에 남으며, 그 폴더를 지워야 함께 지워집니다. 다른 앱 데이터와 마찬가지로, 기기 백업(예: iCloud 백업)을 켜 두었다면 Basin의 데이터도 백업에 포함됩니다. 이 백업은 사용자 본인의 계정으로 Apple이 만들고 관리하며, 개발자는 관여하지 않습니다.

## iCloud 동기화(Basin Pro)

Basin Pro를 구입하면, 같은 Apple 계정으로 로그인한 iPhone과 Mac에서 메모의 글을 똑같이 맞춰 줍니다.

- 동기화되는 것: 제목, 받아쓴 글(서식 포함)과 Basin이 메모마다 보관하는 원본 전사, 요약, 날짜, 즐겨찾기와 고정, 폴더, 메모 사이의 연결, 최근 삭제된 항목에 있는지 여부, 교체 규칙, 메모의 언어 같은 정보, 각 녹음의 파일 이름과 길이. 녹음 자체는 동기화되지 않습니다. 녹음이 완전히 지워지면 그 파일 이름과 지운 시각을 적은 메모가 남아, 다른 기기도 자기 사본을 지웁니다.
- 보관되는 곳: iCloud(Apple의 CloudKit 서비스)에 있는 사용자의 개인 데이터베이스 중 Basin 전용 영역입니다. 사용자의 Apple 계정에 묶여 있으며, 개발자는 이를 보거나 열거나 내려받을 수 없고 Basin 서버를 거치지도 않습니다. 이 데이터는 Apple의 약관과 개인정보 처리방침에 따라 Apple이 보관하며, 전송 중과 Apple 서버에서 암호화됩니다.
- 시작: Basin Pro를 구입한 뒤 다음에 Basin을 열 때 시작됩니다. 기기마다 설정 › iCloud 동기화에서 끌 수 있고(Mac에서는 Basin › 설정), 바꾼 내용은 다음에 Basin을 열 때 적용됩니다.
- 동기화를 끄거나, Basin Pro가 환불되거나, Basin Pro 구독이 끝나면 그 기기는 동기화를 멈춥니다. 기기의 메모는 하나도 지워지지 않고, 이미 iCloud에 있는 내용은 그대로 남습니다.
- 동기화 중 삭제: 한 기기에서 메모를 최근 삭제된 항목으로 옮기거나, 복구하거나, 영구 삭제하면 동기화되는 다른 기기와 iCloud에서도 똑같이 됩니다. 어느 기기에서든 메모를 영구 삭제하면, 그 녹음을 가진 기기도 녹음을 함께 지웁니다 — 그 기기에서 지웠다면 바로, 아니면 지운 지 일주일 뒤입니다. 변경이 닿기 전에 다른 기기에서 덧붙인 녹음은 그 기기에 남을 수 있습니다.
- iCloud에서 메모 지우기: iCloud 동기화를 켠 상태에서 iPhone에서 메모를 영구 삭제하면(최근 삭제된 항목에서 메모를 왼쪽으로 밀고 휴지통 버튼을 누릅니다) iCloud와 동기화되는 다른 기기에서도 지워집니다(녹음 파일 이름과 지운 시각을 적은 메모만 남습니다). 최근 삭제된 항목에 30일 동안 남아 있던 메모도 같은 방식으로 지워집니다. 동기화를 끄거나, 환불되거나, 구독이 끝나거나, 앱을 지워도 이미 iCloud에 있는 내용은 지워지지 않습니다. Basin Pro가 있든 없든, iCloud 저장 공간 관리에서 Basin의 데이터를 지워 iCloud에서 모두 없앨 수도 있습니다. 이렇게 해도 기기에 있는 메모는 지워지지 않고, 아직 iCloud 동기화가 켜진 기기는 메모를 다시 올립니다. 그러니 먼저 기기마다 Basin에서 iCloud 동기화를 끄고 Basin을 다시 연 뒤 지우세요.
- 기기의 iCloud 계정이 바뀌었는지 알기 위해, Basin은 로그인된 계정에 대해 시스템이 주는 토큰을 기기 안에 보관합니다. 이 토큰은 기기를 떠나지 않으며 개발자가 사용자를 알아볼 수 있는 정보가 아닙니다.
- 다른 기기에서 바뀐 내용이 있으면 iCloud가 Basin을 백그라운드에서 잠깐 깨울 수 있습니다. 이때 Basin은 변경 사항을 받아 오고, 앱을 열 때와 같은 기기 안 정리(위젯, 검색, 설정해 둔 경우 자동 내보내기 등)를 하며, 녹음은 하지 않습니다.

## 기기 안의 안전 사본

iCloud 동기화를 켠 기기에서는 Basin이 메모 저장소의 사본 몇 개를 그 기기의 Basin 저장 공간에 보관합니다. 기기가 처음 동기화하기 직전에 만든 사본 하나와, 그 뒤에 만든 최근 사본 다섯 개(최대 6시간에 하나)입니다. 기기 저장 공간이 부족하면 사본을 만들지 않습니다. 사본에는 메모의 글과 정보가 들어 있고 녹음은 들어 있지 않습니다. 동기화에 문제가 생겼을 때 메모를 되살리기 위한 것입니다(iPhone: 설정 › 로컬 사본에서 메모 복구). Basin은 사본을 어디에도 올려 보내지 않습니다. 그 기기의 다른 Basin 데이터와 함께 지워지며("메모가 저장되는 곳" 참조), 다른 앱 데이터와 마찬가지로 기기 백업을 켜 두었다면 백업에 포함됩니다.

## Mac용 Basin(Basin Pro)

Mac용 Basin은 iCloud 동기화로 iPhone에서 넘어온 메모를 보여 줍니다. Mac에서는 메모를 읽고, 검색하고, 복사하고, 내보내고, 제목을 바꾸고, 최근 삭제된 항목으로 옮기거나 거기서 복구할 수 있으며, 이 변경은 다른 기기에도 동기화됩니다. Mac용 Basin은 녹음, 받아쓰기, 오디오 재생, 요약을 하지 않고 마이크도 쓰지 않습니다. 메모, 설정, 위에서 설명한 안전 사본은 Mac 안의 샌드박스 저장 공간에 보관합니다.

## Basin Pro 구입

Basin Pro는 앱 내 구입입니다. 1개월·3개월마다 자동으로 갱신되는 구독이나, 한 번 구입하는 평생 이용권 중에서 고릅니다. 구입·갱신·해지는 Apple이 App Store를 통해 처리하며, 개발자는 결제 정보, 이름, Apple 계정을 볼 수 없습니다. 구독은 Apple 계정 설정에서 관리하거나 해지합니다. Basin은 사용자의 Apple 계정에 Basin Pro(진행 중인 구독 또는 평생 이용권)가 있는지, 첫 달 무료를 아직 받을 수 있는지 기기 안에서 Apple의 StoreKit에 확인하고, Basin Pro가 있는지를 기기에 기억해 두어 오프라인에서도 Basin Pro를 쓸 수 있게 합니다. 개발자는 다른 모든 개발자와 마찬가지로 Apple이 제공하는 App Store 판매 보고서를 보며, 여기에는 사용자의 이름, 연락처, Apple 계정이 들어 있지 않습니다.

Basin Pro를 구입하지 않거나, 환불받거나, 구독이 끝나도 메모는 하나도 지워지지 않습니다. 환불되거나 구독이 끝나면 iCloud 동기화, 자동 내보내기와 그 밖의 Basin Pro 기능이 멈춥니다. Mac에 이미 내려와 있던 메모는 그대로 남아 계속 읽고 복사할 수 있습니다.

## 받아쓰기와 요약은 기기 안에서

- 음성은 Apple의 Speech 프레임워크로 기기 안에서 글로 바뀝니다. 어떤 언어로 처음 녹음할 때 iOS가 그 언어의 Apple 음성 인식 모델을 내려받을 수 있습니다. 이 내려받기는 iOS가 처리하며 녹음이나 글이 함께 보내지지 않습니다.
- 요약과 제목 제안은 지원되는 기기에서 Apple Intelligence(Apple의 기기 내 Foundation Models)로 기기 안에서 만들어집니다.
- 관련 메모 추천도 기기 안에서 계산됩니다.
- Mac용 Basin은 이런 처리를 하지 않고, iPhone이 만든 결과를 보여 줍니다.

## 제3자 제공 없음

Basin은 녹음이나 글을 개발자나 제3자에게 보내지 않습니다. Basin Pro에 포함된 iCloud 동기화(메모의 글을 사용자 본인의 iCloud에 보관)를 빼면, 정보는 사용자가 직접 공유하거나 내보낼 때만 기기를 떠납니다. 예를 들어 메모를 텍스트·이미지·오디오 파일로 공유하거나, Obsidian에서 열거나, X에 게시하거나, Apple의 미리 알림 앱에 미리 알림을 만들거나, 사용자가 고른 위치에 Markdown 파일로 내보낼 때(Basin Pro의 자동 내보내기 포함)입니다. 이때 정보는 사용자가 고른 앱·서비스·위치로 전달되며, 그 뒤에는 해당 앱이나 서비스의 개인정보 처리방침이 적용됩니다. 클라우드 서비스가 동기화하는 위치를 고르면, 내보낸 파일에는 그 서비스의 방침이 적용됩니다.

## 권한

- 마이크(iPhone, Apple Watch): 음성 메모를 녹음할 때만 사용합니다.
- 미리 알림: 메모에서 미리 알림을 만들 때만 요청하며, 그 미리 알림을 만들거나 보여 줄 때만 사용합니다.
- 내보내기 위치(Basin Pro, iPhone·Mac): Basin은 사용자가 내보내기용으로 고른 위치에만 쓸 수 있습니다. 자동 내보내기가 그 위치에 메모의 Markdown 파일을 계속 쓸 수 있도록 그 위치를 기기에 기억합니다. 설정 › 고급 내보내기에서 다른 위치를 고르거나 자동 내보내기를 끌 수 있습니다.
- iCloud(Basin Pro): 기기에 로그인된 iCloud 계정을 사용하며, 암호를 묻지 않습니다.

마이크와 미리 알림 권한은 설정 앱에서 언제든 끌 수 있고, 위치에 파일을 쓰는 일은 Basin의 설정 › 고급 내보내기에서 자동 내보내기를 끄면 멈추며, Basin의 iCloud 사용은 Apple 계정의 iCloud 설정에서 끌 수 있습니다.

## 어린이

Basin은 어린이를 포함해 누구에게서도 개인정보를 수집하지 않습니다.

## 방침의 변경

이 방침이 바뀌면 새 시행일과 함께 이 페이지에 새 버전을 올립니다.

## 문의

이 방침에 관한 문의: i7434554@gmail.com
