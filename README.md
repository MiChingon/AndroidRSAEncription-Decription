# AndroidRSAEncription-Decription
Android RSA Encription and Decription Repo.

Antes de usar esta clase se debe importar las dependencias de SpongyCastle en el Gradle.

dependencies {
	compile 'com.madgag.spongycastle:core:1.51.0.0'
	compile 'com.madgag.spongycastle:prov:1.51.0.0'
	compile 'com.madgag.spongycastle:pkix:1.51.0.0'
	compile 'com.madgag.spongycastle:pg:1.51.0.0'
}

Estas se usaran para generar las llaves privadas y publicas RSA en caso de no contar con ellas.

Para que este codigo funcione, es necesario que importen la clase Base64 de apache "apache.commons.codec.binary.Base64",
ya que no funciona con la que viene precargada con el sdk de android (Util.Base64).

Para saber como importar la clase Base64 contacten a Carlos Briseño (solo si eres parte del equipo de desarrollo).
