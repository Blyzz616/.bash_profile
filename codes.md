(Copy Pasta Below)[]

# Reset
Color_Off='\033[0m'       # Text Reset  

# Regular Colors
Black='\033[0;30m'        # Black  
Red='\033[0;31m'          # Red  
Green='\033[0;32m'        # Green  
Yellow='\033[0;33m'       # Yellow  
Blue='\033[0;34m'         # Blue  
Purple='\033[0;35m'       # Purple  
Cyan='\033[0;36m'         # Cyan  
White='\033[0;37m'        # White  

# Bold
BBlack='\033[1;30m'       # Black  
BRed='\033[1;31m'         # Red  
BGreen='\033[1;32m'       # Green  
BYellow='\033[1;33m'      # Yellow  
BBlue='\033[1;34m'        # Blue  
BPurple='\033[1;35m'      # Purple  
BCyan='\033[1;36m'        # Cyan  
BWhite='\033[1;37m'       # White  

# Underline
UBlack='\033[4;30m'       # Black  
URed='\033[4;31m'         # Red  
UGreen='\033[4;32m'       # Green  
UYellow='\033[4;33m'      # Yellow  
UBlue='\033[4;34m'        # Blue  
UPurple='\033[4;35m'      # Purple  
UCyan='\033[4;36m'        # Cyan  
UWhite='\033[4;37m'       # White  

# Background
On_Black='\033[40m'       # Black  
On_Red='\033[41m'         # Red  
On_Green='\033[42m'       # Green  
On_Yellow='\033[43m'      # Yellow  
On_Blue='\033[44m'        # Blue  
On_Purple='\033[45m'      # Purple  
On_Cyan='\033[46m'        # Cyan  
On_White='\033[47m'       # White  

# High Intensity
IBlack='\033[0;90m'       # Black  
IRed='\033[0;91m'         # Red  
IGreen='\033[0;92m'       # Green  
IYellow='\033[0;93m'      # Yellow  
IBlue='\033[0;94m'        # Blue  
IPurple='\033[0;95m'      # Purple  
ICyan='\033[0;96m'        # Cyan  
IWhite='\033[0;97m'       # White  

# Bold High Intensity
BIBlack='\033[1;90m'      # Black  
BIRed='\033[1;91m'        # Red  
BIGreen='\033[1;92m'      # Green  
BIYellow='\033[1;93m'     # Yellow  
BIBlue='\033[1;94m'       # Blue  
BIPurple='\033[1;95m'     # Purple  
BICyan='\033[1;96m'       # Cyan  
BIWhite='\033[1;97m'      # White  

# High Intensity backgrounds
On_IBlack='\033[0;100m'   # Black  
On_IRed='\033[0;101m'     # Red  
On_IGreen='\033[0;102m'   # Green  
On_IYellow='\033[0;103m'  # Yellow  
On_IBlue='\033[0;104m'    # Blue  
On_IPurple='\033[0;105m'  # Purple  
On_ICyan='\033[0;106m'    # Cyan  
On_IWhite='\033[0;107m'   # White  


# Copy
```
Colour_Off='\033[0m';Black='\033[0;30m';Red='\033[0;31m';Green='\033[0;32m';Yellow='\033[0;33m';Blue='\033[0;34m';Purple='\033[0;35m';Cyan='\033[0;36m';White='\033[0;37m';BBlack='\033[1;30m';BRed='\033[1;31m';BGreen='\033[1;32m';BYellow='\033[1;33m';BBlue='\033[1;34m';BPurple='\033[1;35m';BCyan='\033[1;36m';BWhite='\033[1;37m';UBlack='\033[4;30m';URed='\033[4;31m';UGreen='\033[4;32m';UYellow='\033[4;33m';UBlue='\033[4;34m';UPurple='\033[4;35m';UCyan='\033[4;36m';UWhite='\033[4;37m';On_Black='\033[40m';On_Red='\033[41m';On_Green='\033[42m';On_Yellow='\033[43m';On_Blue='\033[44m';On_Purple='\033[45m';On_Cyan='\033[46m';On_White='\033[47m';IBlack='\033[0;90m';IRed='\033[0;91m';IGreen='\033[0;92m';IYellow='\033[0;93m';IBlue='\033[0;94m';IPurple='\033[0;95m';ICyan='\033[0;96m';IWhite='\033[0;97m';BIBlack='\033[1;90m';BIRed='\033[1;91m';BIGreen='\033[1;92m';BIYellow='\033[1;93m';BIBlue='\033[1;94m';BIPurple='\033[1;95m';BICyan='\033[1;96m';BIWhite='\033[1;97m';On_IBlack='\033[0;100m';On_IRed='\033[0;101m';On_IGreen='\033[0;102m';On_IYellow='\033[0;103m';On_IBlue='\033[0;104m';On_IPurple='\033[0;105m';On_ICyan='\033[0;106m';On_IWhite='\033[0;107m'

echo -e "\033[4;37mRegular\033[0m"
echo -ne "$Black Black \033[0m (Black) "; echo " $Black"
echo -ne "$Red Red \033[0m"; echo " $Red"
echo -ne "$Green Green \033[0m"; echo " $Green"
echo -ne "$Yellow Yellow \033[0m"; echo " $Yellow"
echo -ne "$Blue Blue \033[0m"; echo " $Blue"
echo -ne "$Purple Purple \033[0m"; echo " $Purple"
echo -ne "$Cyan Cyan \033[0m"; echo " $Cyan"
echo -ne "$White White \033[0m"; echo " $White"
echo -e "
\033[4;37mBold\033[0m"
echo -ne "$BBlack Black\033[0m"; echo " $BBlack"
echo -ne "$BRed Red\033[0m"; echo " $BRed"
echo -ne "$BGreen Green\033[0m"; echo " $BGreen"
echo -ne "$BYellow Yellow\033[0m"; echo " $BYellow"
echo -ne "$BBlue Blue\033[0m"; echo " $BBlue"
echo -ne "$BPurple Purple\033[0m"; echo " $BPurple"
echo -ne "$BCyan Cyan\033[0m"; echo " $BCyan"
echo -ne "$BWhite White\033[0m"; echo " $BWhite"
echo -e "
\033[4;37mUnderline\033[0m"
echo -ne "$UBlack Black\033[0m"; echo " $UBlack"
echo -ne "$URed Red\033[0m"; echo " $URed"
echo -ne "$UGreen Green\033[0m"; echo " $UGreen"
echo -ne "$UYellow Yellow\033[0m"; echo " $UYellow"
echo -ne "$UBlue Blue\033[0m"; echo " $UBlue"
echo -ne "$UPurple Purple\033[0m"; echo " $UPurple"
echo -ne "$UCyan Cyan\033[0m"; echo " $UCyan"
echo -ne "$UWhite White\033[0m"; echo " $UWhite"
echo -e "
\033[4;37mBackground\033[0m"
echo -ne "$On_Black Black\033[0m"; echo " $On_Black"
echo -ne "$On_Red Red\033[0m"; echo " $On_Red"
echo -ne "$On_Green Green\033[0m"; echo " $On_Green"
echo -ne "$On_Yellow Yellow\033[0m"; echo " $On_Yellow"
echo -ne "$On_Blue Blue\033[0m"; echo " $On_Blue"
echo -ne "$On_Purple Purple\033[0m"; echo " $On_Purple"
echo -ne "$On_Cyan Cyan\033[0m"; echo " $On_Cyan"
echo -ne "$On_White White\033[0m"; echo " $On_White"
echo -e "
\033[4;37mHigh Intensity\033[0m"
echo -ne "$IBlack Black\033[0m"; echo " $IBlack"
echo -ne "$IRed Red\033[0m"; echo " $IRed"
echo -ne "$IGreen Green\033[0m"; echo " $IGreen"
echo -ne "$IYellow Yellow\033[0m"; echo " $IYellow"
echo -ne "$IBlue Blue\033[0m"; echo " $IBlue"
echo -ne "$IPurple Purple\033[0m"; echo " $IPurple"
echo -ne "$ICyan Cyan\033[0m"; echo " $ICyan"
echo -ne "$IWhite White\033[0m"; echo " $IWhite"
echo -e "
\033[4;37mBold High Intensity\033[0m"
echo -ne "$BIBlack Black\033[0m"; echo " $BIBlack"
echo -ne "$BIRed Red\033[0m"; echo " $BIRed"
echo -ne "$BIGreen Green\033[0m"; echo " $BIGreen"
echo -ne "$BIYellow Yellow\033[0m"; echo " $BIYellow"
echo -ne "$BIBlue Blue\033[0m"; echo " $BIBlue"
echo -ne "$BIPurple Purple\033[0m"; echo " $BIPurple"
echo -ne "$BICyan Cyan\033[0m"; echo " $BICyan"
echo -ne "$BIWhite White\033[0m"; echo " $BIWhite"
echo -e "
\033[4;37mHigh Intensity backgrounds\033[0m"
echo -ne "$On_IBlack Black\033[0m"; echo " $On_IBlack"
echo -ne "$On_IRed Red\033[0m"; echo " $On_IRed"
echo -ne "$On_IGreen Green\033[0m"; echo " $On_IGreen"
echo -ne "$On_IYellow Yellow\033[0m"; echo " $On_IYellow"
echo -ne "$On_IBlue Blue\033[0m"; echo " $On_IBlue"
echo -ne "$On_IPurple Purple\033[0m"; echo " $On_IPurple"
echo -ne "$On_ICyan Cyan\033[0m"; echo " $On_ICyan"
echo -ne "$On_IWhite White\033[0m"; echo " $On_IWhite"
echo -e "
\033[4;37mReset\033[0m"
echo -ne "$Colour_Off Colour_Off\033[0m"; echo " $Colour_Off"
echo -e "

"
```
