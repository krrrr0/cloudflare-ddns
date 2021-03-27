# Use Cloudflare for DDNS
Using the Cloudflare API, you can make your domian's DNS records follow your dynamic ip address automatically.  
  
See the instructions on the files.  
Place the files somewhere, and set up a cron job to run `cloudflare-ddns.sh` automatically every 5 minutes.  
You will only need `cloudflare-dns-id.sh` when setting up.  
  
Good luck. You are on your own.

## 한국어 (Korean)
클라우드플레어의 API를 사용해서, 클라우드플레어에 등록된 도메인을 DDNS로 사용할 수 있습니다.  
파일에 있는 설명을 확인해서 설정한 다음, 적절한 디렉토리에 파일을 놓고 `cloudflare-ddns.sh`를 5분마다 실행할 크론잡을 설정하세요.
`cloudflare-dns-id`는 초기 설정 시에만 필요한 파일이니, `cloudlfare-ddns.sh`의 작성을 완료한 다음에는 삭제하셔도 됩니다.  
  
행운을 빕니다.

