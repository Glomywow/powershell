while(1) 
{ 
sleep (2)
$cpu = (Get-Process 'dllhost' |Where-Object -Property description -Like 'com surrogate' | where {$_.PercentProcessorTime -ge 80})
$proc = (Get-Process 'dllhost' | Where-Object -Property description -like 'com surrogate' |where {$_.WorkingSet64 -gt 1900mb})
if ($proc)
{
Stop-Process -id $proc.id -force
                $encoding = [System.Text.Encoding]::UTF8
                
                $smtp = "someuser@test.ru" 
 
                $to = "someuser@test.ru" 
 
                $from = "someuser@test.ru" 

                $cc = "someuser@test.ru"
 
                $subject = "Dllhost"  
 
                $body = "Опаньки, кажется дллхост был больше 1900мб, остановил его.<br>Это казань<br> " 
 

                $body += "<p>&nbsp;</p>
<table style='table-layout: fixed;' border='0' width='450' cellpadding='0'>
	<tbody>
		<tr>
			<td class='logo-td' align='left' valign='middle' width='87'>
				<p style='margin-right: 10px; font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'>
					<a class='clink logo-container' style='text-decoration: none;' href='https://twitch.tv/badjokr'><img class='sig-logo' src='https://htmlsigs.s3.amazonaws.com/logos/files/000/347/061/landscape/badjokr_2gud4me.png' alt='' width='77' height='80' border='0' /></a>
				</p>
			</td>
			<td class='content-td' align='left' nowrap='nowrap' width='373'>
				<p style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; color: #212121; margin-bottom: 10px;'><span class='txt signature_name-target sig-hide' style='font-weight: bold; color: #ec0000; display: inline;'>badjokr</span> <span class='title-sep sep' style='display: inline;'>/</span> <span class='txt signature_jobtitle-target sig-hide' style='color: #ec0000; display: inline;'>Twitch Channel Moderator</span>					<span class='email-sep break' style='display: inline;'><br /></span> <a class='link email signature_email-target sig-hide' style='color: #47afcc; text-decoration: none; display: inline;' href='mailto:badjokr@420blaze.it'>badjokr@420blaze.it</a>
					<span class='signature_email-sep sep' style='display: none;'>/</span> <span class='txt signature_mobilephone-target sig-hide' style='color: #ec0000;'></span></p>
				<p style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'><span class='txt signature_companyname-target sig-hide' style='font-weight: bold; color: #ec0000;'></span> <span class='company-sep break' style='display: inline;'><br /></span> <span class='txt office-sep sep' style='color: #ec0000; display: none;'>Office:</span>					<span class='txt signature_officephone-target sig-hide' style='color: #ec0000;'></span> <span class='txt fax-sep sep' style='color: #ec0000; display: none;'>/ Fax:</span> <span class='txt signature_fax-target sig-hide' style='color: #ec0000;'></span>					<span class='address-sep break'></span> <span class='txt signature_address-target sig-hide' style='color: #ec0000; display: inline;'>@</span><a class='link signature_website-target sig-hide' style='color: #47afcc; text-decoration: none; display: inline;'
					href='https://twitch.tv/RussianPaladin/'>twitch.tv/RussianPaladin</a><span class='address2-sep break' style='display: block;'></span> <span class='txt signature_address2-target sig-hide' style='color: #ec0000; display: inline;'>@</span><a class='link signature_website-target sig-hide'
					style='color: #47afcc; text-decoration: none; display: inline;' href='https://twitch.tv/MrElectrifyBF/'>twitch.tv/MrElectrifyBF</a> <span class='website-sep break' style='display: inline;'><br /></span> <a class='link signature_website-target sig-hide'
					style='color: #47afcc; text-decoration: none; display: inline;' href='https://twitch.tv/badjokr'>twitch.tv/badjokr</a></p>
				<p class='social-list' style='font-size: 0px; line-height: 0; font-family: Helvetica, Arial, sans-serif;'>
					<a class='social signature_twitter-target sig-hide' style='text-decoration: none; display: inline;' href='https://twitter.com/badjokr'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/twitter.png' alt='Twitter' width='32' height='32' /></a><span class='signature_twitter-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span>
					<a class='social signature_youtube-target sig-hide' style='text-decoration: none; display: inline;' href='https://www.youtube.com/channel/UCo0RGt1-zq5RRll85X_YhFw'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/youtube.png' alt='Youtube' width='32' height='32' /></a><span class='signature_youtube-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span>
					<a class='social signature_soundcloud-target sig-hide' style='display: inline; text-decoration: none;' href='https://soundcloud.com/n-h-i-m/sets/paladins-adventure'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/soundcloud.png' alt='Soundcloud' width='32' height='32' /></a><span class='signature_soundcloud-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span></p>
			</td>
		</tr>
		<tr>
			<td colspan='2'>
				<p class='banner-container' style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'>
					<a class='clink banner-container' href='https://twitch.tv/badjokr'><img class='sig-banner' style='display: inline-block !important; background-position: 0px 0px;' src='https://i.imgur.com/L1kLq0b.png' alt='That guy doe' width='300px' height=
60px' border='0' /></a>
				</p>
			</td>
		</tr>
		<tr>
			<td colspan='2'>&nbsp;</td>
		</tr>
		<tr>
			<td colspan='2'>&nbsp;</td>
		</tr>
	</tbody>
</table>"

                Send-MailMessage -From $from -To $to -Cc $cc -Subject $subject -Body $body -SmtpServer $smtp -BodyAsHtml -Encoding $encoding

}
elseif($cpu){
Stop-Process -id $proc.id -force
                $encoding = [System.Text.Encoding]::UTF8
                
                $smtp = "someuser@test.ru" 
 
                $to = "someuser@test.ru" 
 
                $from = "someuser@test.ru" 

                $cc = "someuser@test.ru"
 
                $subject = "Dllhost"  
 
                $body = "Опаньки, кажется дллхост не кушал оперативку, а втопил проц в 100-ку, остановил его.<br>Это казань<br> " 
 
                $body += "<p>&nbsp;</p>
<table style='table-layout: fixed;' border='0' width='450' cellpadding='0'>
	<tbody>
		<tr>
			<td class='logo-td' align='left' valign='middle' width='87'>
				<p style='margin-right: 10px; font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'>
					<a class='clink logo-container' style='text-decoration: none;' href='https://twitch.tv/badjokr'><img class='sig-logo' src='https://htmlsigs.s3.amazonaws.com/logos/files/000/347/061/landscape/badjokr_2gud4me.png' alt='' width='77' height='80' border='0' /></a>
				</p>
			</td>
			<td class='content-td' align='left' nowrap='nowrap' width='373'>
				<p style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; color: #212121; margin-bottom: 10px;'><span class='txt signature_name-target sig-hide' style='font-weight: bold; color: #ec0000; display: inline;'>badjokr</span> <span class='title-sep sep' style='display: inline;'>/</span> <span class='txt signature_jobtitle-target sig-hide' style='color: #ec0000; display: inline;'>Twitch Channel Moderator</span>					<span class='email-sep break' style='display: inline;'><br /></span> <a class='link email signature_email-target sig-hide' style='color: #47afcc; text-decoration: none; display: inline;' href='mailto:badjokr@420blaze.it'>badjokr@420blaze.it</a>
					<span class='signature_email-sep sep' style='display: none;'>/</span> <span class='txt signature_mobilephone-target sig-hide' style='color: #ec0000;'></span></p>
				<p style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'><span class='txt signature_companyname-target sig-hide' style='font-weight: bold; color: #ec0000;'></span> <span class='company-sep break' style='display: inline;'><br /></span> <span class='txt office-sep sep' style='color: #ec0000; display: none;'>Office:</span>					<span class='txt signature_officephone-target sig-hide' style='color: #ec0000;'></span> <span class='txt fax-sep sep' style='color: #ec0000; display: none;'>/ Fax:</span> <span class='txt signature_fax-target sig-hide' style='color: #ec0000;'></span>					<span class='address-sep break'></span> <span class='txt signature_address-target sig-hide' style='color: #ec0000; display: inline;'>@</span><a class='link signature_website-target sig-hide' style='color: #47afcc; text-decoration: none; display: inline;'
					href='https://twitch.tv/RussianPaladin/'>twitch.tv/RussianPaladin</a><span class='address2-sep break' style='display: block;'></span> <span class='txt signature_address2-target sig-hide' style='color: #ec0000; display: inline;'>@</span><a class='link signature_website-target sig-hide'
					style='color: #47afcc; text-decoration: none; display: inline;' href='https://twitch.tv/MrElectrifyBF/'>twitch.tv/MrElectrifyBF</a> <span class='website-sep break' style='display: inline;'><br /></span> <a class='link signature_website-target sig-hide'
					style='color: #47afcc; text-decoration: none; display: inline;' href='https://twitch.tv/badjokr'>twitch.tv/badjokr</a></p>
				<p class='social-list' style='font-size: 0px; line-height: 0; font-family: Helvetica, Arial, sans-serif;'>
					<a class='social signature_twitter-target sig-hide' style='text-decoration: none; display: inline;' href='https://twitter.com/badjokr'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/twitter.png' alt='Twitter' width='32' height='32' /></a><span class='signature_twitter-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span>
					<a class='social signature_youtube-target sig-hide' style='text-decoration: none; display: inline;' href='https://www.youtube.com/channel/UCo0RGt1-zq5RRll85X_YhFw'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/youtube.png' alt='Youtube' width='32' height='32' /></a><span class='signature_youtube-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span>
					<a class='social signature_soundcloud-target sig-hide' style='display: inline; text-decoration: none;' href='https://soundcloud.com/n-h-i-m/sets/paladins-adventure'><img style='margin-bottom: 2px; border: none; display: inline;' src='https://s3.amazonaws.com/htmlsig-assets/round/soundcloud.png' alt='Soundcloud' width='32' height='32' /></a><span class='signature_soundcloud-sep' style='white-space: nowrap;'><img src='https://s3.amazonaws.com/htmlsig-assets/spacer.gif' alt='' width='2' /></span></p>
			</td>
		</tr>
		<tr>
			<td colspan='2'>
				<p class='banner-container' style='font-family: Helvetica, Arial, sans-serif; font-size: 14px; line-height: 16px; margin-bottom: 10px;'>
					<a class='clink banner-container' href='https://twitch.tv/badjokr'><img class='sig-banner' style='display: inline-block !important; background-position: 0px 0px;' src='https://i.imgur.com/L1kLq0b.png' alt='That guy doe' width='300px' height=
60px' border='0' /></a>
				</p>
			</td>
		</tr>
		<tr>
			<td colspan='2'>&nbsp;</td>
		</tr>
		<tr>
			<td colspan='2'>&nbsp;</td>
		</tr>
	</tbody>
</table>"

}
else{
    
}
}
