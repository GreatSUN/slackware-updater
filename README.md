# slackware-updater
Makes use of slackpkg and according config files but analysis mirror list automatically and chooses the fastest mirror at the moment it runs. Also it checks if there is an update available in any case. Support is given for current version and current (development/unstable) versions.
  
## prerequisities
* curl
* slackpkg
* bash
* current version of /etc/slackpkg/mirrors
  
## usage (also available when running with --help)
**Usage:** /usr/bin/updateSlacky [options]  
  
  
<code><table cols=2 border=1>
  <tr><td colspan=2><b>Options:</b></td></tr>  
  <tr><td align="right">
    includeCurrent:<br>
    -includeCurrent:<br>
    --includeCurrent:
    </td><td>
    &nbsp;Download from fastest mirror (don't care about version or current)
    </td>
  </tr>
  <tr><td align="right">
    current:<br>
    -current:<br>
    --current:<br>
    </td><td>
    &nbsp;Download from fastest current mirror only
    </td>
  </tr>
  <tr><td align="right">
    help:<br>
    -help:<br>
    --help:<br>
    </td><td>
    This usage information
    </td>
  </tr>
  </table></code>  
  
**Default download type (if no option given) is version only!**
