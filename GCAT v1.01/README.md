# GCAT-Setup

# ---------------------------------------------------------------------------------------------------------------------------------------------------------------
																GCAT v1.01 - prerequisite
# ---------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Check whether you have a jdk/jre installed in your system.

2. Make sure you have winmerge software installed in your system.

3. Make sure you have access to Vodafone Git repository.

# ---------------------------------------------------------------------------------------------------------------------------------------------------------------
																GCAT v1.01 - Setup
# ---------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Open cmd run Java –version (Check the installed jdk/jre version) [Make sure you have jdk/jre 1.8 or above]

2. Based on the installed version download either 32 bit/64 bit build.

3. Create path C:\Program Files (x86)\tool\GCAT

4. Please make sure you download the correct version based on your jdk/jre version.

5. Open Application.properties file and update the below path

		a. output_file_directory – Output directory where the generated configuration file has to be created

		b. git_repo_path – git path to clone the configuration file from git

		c. config_file_base_path – Path to copy the files that are cloned from git

		d. git_bash_path – Path to copy the files that are cloned from git
	
6. Now, Launch the application by selecting GCAT v-1.01.exe

# ---------------------------------------------------------------------------------------------------------------------------------------------------------------
																GCAT - V1.01 has the following Changes
# ---------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Converted the entire application from .net to java

2. User will be able to create new partners

3. Users will be able to create new operation

4. Users can use 2 modes, Browse and Generate (Browse mode - To view the contents, Generate - To add/update the existing contents in cfg files)

5. Users can also add existing operation to a new/existing partners

6. User has privilege to compare the generated Files with the original file and view only the modified contents.

7. Users can directly do a checkin and checkout

8. The application also has an userguide under help section.