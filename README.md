# English

This repository is obsolet because the integration of Moodle and ownCloud was implemented in other repositories:

* In ownCloud the OAuth 2.0 Protocol was implemented to secure WebDAV and APIs (like the OCS Share API)
	* Core changes: see Pull Request [owncloud/core#26742](https://github.com/owncloud/core/pull/26742) and its backport [owncloud/core#27370](https://github.com/owncloud/core/pull/27370)
	* OAuth 2.0 implementation: see [`oauth2` App](https://github.com/owncloud/oauth2)
* In Moodle some plugins were implemented to support different use cases (focusing on integrating ownCloud into Moodle)
	* Plugin to manage authentication and authorization with OAuth 2.0: [Admin tool `oauth2owncloud`](https://github.com/pssl16/moodle-tool_oauth2owncloud)
	* Plugin for downloading and linking files from ownCloud: [Repository `owncloud`](https://github.com/pssl16/moodle-repository_owncloud)
	* Plugin for creating folders in ownCloud for collaborative work: [Activity `collaborativefolders`](https://github.com/pssl16/moodle-mod_collaborativefolders)

This work will be presented on Wednesday, 15th March 2017, at 14:00 o'clock (GMT+1) at the University of Münster. You can watch live [here](https://www.youtube.com/watch?v=2GYvoP36vFc) (unfortunately only in German). Furthermore the project's documentation is currently under construction and can be found at [pssl16.github.io](https://pssl16.github.io/).

# Deutsch

Dieses Repository is obsolet, da die Integration von Moodle und ownCloud in anderen Repositories implementiert wurde:

* In ownCloud wurde das OAuth 2.0 Protokoll zur Absicherung von WebDAV und APIs (wie die OCS Share API) implementiert
	* Anpassungen des Cores: siehe Pull Request [owncloud/core#26742](https://github.com/owncloud/core/pull/26742) und dessen Backport [owncloud/core#27370](https://github.com/owncloud/core/pull/27370)
	* OAuth 2.0 Implementierung: siehe [`oauth2` App](https://github.com/owncloud/oauth2)
* In Moodle wurden einige Plugins implementiert, im unterschiedliche Use Cases zu unterstützen (fokussiert auf die Integration von ownCloud in Moodle)
	* Plugin zur Verwaltung der Authentifizierung und Autorisierung mit OAuth 2.0: [Admin tool `oauth2owncloud`](https://github.com/pssl16/moodle-tool_oauth2owncloud)
	* Plugin zum Herunterladen und Verlinken von Dateien aus ownCloud: [Repository `owncloud`](https://github.com/pssl16/moodle-repository_owncloud)
	* Plugin zum Erstellen von Ordnern in ownCloud für kollaboratives Arbeiten: [Activity `collaborativefolders`](https://github.com/pssl16/moodle-mod_collaborativefolders)

Diese Arbeit wird am Mittwoch, den 15. März 2017, um 14:00 Uhr (GMT+1) an der Universität Münster präsentiert. Sie können [hier](https://www.youtube.com/watch?v=2GYvoP36vFc) live zuschauen. Außerdem wird momentan eine Projektdokumentation erstellt, die unter [pssl16.github.io](https://pssl16.github.io/) zu finden ist.
