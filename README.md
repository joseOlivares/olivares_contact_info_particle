# olivares_contact_info_particle
Contact information particle, version 2  for Gantry 5.3.2+ (Joomla 4 or 3 compatible), using UIkit 3.x and FontAwesome 5.x

Hi my name is Jose Luis Olivares, this is my particle to show site Contact Information for Gantry 5.3.2+ 
If you appreciate my effort, please endorse my skills on Linkedin (https://www.linkedin.com/in/jolivaress/) or making a voluntary donation through Paypal https://paypal.me/joolivares 

You can see an example implemented in this website I made (https://iconnsv.com)

#Installation on Joomla 3.x / 4.x:

1-Copy the olivares_contact_info.html.twig and olivares_contact_info.yaml files to root/templates/TEMPLATE_DIR/custom/particles (if the particles folder does not exist, you have to create it manually)

2-Copy the _olivares-contact-info.scss file to root/templates/TEMPLATE_DIR/custom/scss (if the scss folder does not exists, you will need to create it manually)

3- Add the following code in your custom.scss file.

	@import "dependencies";
	@import "olivares-contact-info"; /* Olivares Contact Info Particle */

  If the custom.scss file does not exists, you will need to create it manually. Also, make sure your custom.scss file has the @import "dependencies"; code at the very top.
