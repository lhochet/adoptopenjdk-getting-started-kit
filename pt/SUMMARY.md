# Summary

* [Introdução](README.md)
* [Adote o OpenJDK - Iniciando](adopt-openjdk-getting-started/adopt_openjdk_-_getting_started.md)
   * [O que é o OpenJDK ?](adopt-openjdk-getting-started/what_is_openjdk.md)
   * [Sobre o OCA](adopt-openjdk-getting-started/about_oca_-_signing_the_oca.md)
   * [Escreva no Adopt OpenJDK & Adopt-a-JSR](adopt-openjdk-getting-started/write_up_on_the_adopt_openjdk_&_adopt-a-jsr_programs.md)
   * [Hand-out (flyer) para atendentes das seções/conferencias do Adopt OpenJDK](adopt-openjdk-getting-started/hand-out_for_attendees_of_the_adopt_openjdk_sessions_also_applicable_for_conferences.md)
   * [JUG hand-out (flyer) templates customizados](adopt-openjdk-getting-started/custom_jug_hand-out_template.md)
   * [Tabela de OSes & IDEs](adopt-openjdk-getting-started/table_of_supported_oses_&_ides.md)
   * [OpenJDK Build Benchmarks](adopt-openjdk-getting-started/openjdk-build-benchmarks.md)
   * [OpenJDK Bug database (JIRA)](adopt-openjdk-getting-started/openjdk_bug_database_jira.md)
   * [Instale o comando tree](adopt-openjdk-getting-started/install_the_tree_command.md)
* [Maquinas Virtuais](virtual-machines/virtual_machines.md)
   * [VMs configuradas](virtual-machines/ready-made_vm.md)
   * [Faça sua própria VM](virtual-machines/build_your_own_vm.md)
   * [Faça sua própria VM light-weight](virtual-machines/build_your_own_lightweight_vm.md)
   * [Compartindo arquivos locais com sua VM](virtual-machines/sharing_host_folder_with_guest_vm.md)
* [Binaries](binaries/binaries.md)
   * [OpenJDK Early Access](binaries/openjdk_early_access.md)
   * [JTReg do AdoptOpenJDK BuildFarm](binaries/jtreg_from_buildfarm.md)
   * [Faça o seu proprio OpenJDK](binaries/build_your_own_openjdk.md)
       * [Build do OpenJDK 8](binaries/build_openjdk_8.md)
       * [Build do OpenJDK 9](binaries/build_openjdk_9.md)
* [Codigo fonte](source-code/source_code.md)
   * [Integrando o OpenJDK com sua IDE](source-code/loading_openjdk_into_ide.md)
       * [IntelliJ](source-code/loading_openjdk_in_intellij.md)
       * [Eclipse](source-code/loading_openjdk_in_eclipse.md)
       * [Netbeans](source-code/loading_openjdk_in_netbeans.md)
* [Projetos do OpenJDK](openjdk-projects/openjdk_projects.md)
   * [Penrose](openjdk-projects/penrose.md)
   * [Nashorn](openjdk-projects/nashorn.md)
   * [JMH](openjdk-projects/jmh.md)
   * [Kulla](openjdk-projects/kulla.md)
   * [Valhalla](openjdk-projects/valhalla.md)
* [Passos intermediários](intermediate-steps/intermediate_steps.md)
   * [Veja a estrutura de diversos diretorios e projetos do OpenJDK](intermediate-steps/see_directory_structure_of_various_openjdk_projects.md)
       * [OpenJDK8 estrutura dos diretórios](intermediate-steps/openjdk8_directory_structures.md)
       * [OpenJDK9 estrutura dos diretórios](intermediate-steps/openjdk9_directory_structures.md)
   * [Argumentos de linha de comando para otimização e performance](intermediate-steps/command-line_arguments_for_build_performance_optimisation.md)
   * [JEPs - JDK Propostas de melhorias](intermediate-steps/jeps_-_jdk_enhancement_proposals.md)
   * [Projetos do Adopt OpenJDK](adoptopenjdk-projects/adopt_openjdk_projects.md)
       * [Betterrev](adoptopenjdk-projects/adoptopenjdk_projects_betterrev.md)
       * [Milling Project Coin](intermediate-steps/milling_project_coin.md)
       * [Removendo warnings indesejados](intermediate-steps/cleaning_up_build_warnings.md)
   * [OpenJDK Guia para desenvolvedores](intermediate-steps/openjdk_developers_guide.md)
   * [Exemplo de mudancas e contribuições no OpenJDK](intermediate-steps/example_changesets_of_contributions_into_the_openjdk.md)
   * [Patches - como criar e submete-los (webrev)](intermediate-steps/patches_-_how_to_create_and_submit_them_webrev.md)
   * [Analises de codigo de prjetos OpenJDK](intermediate-steps/code_analysis_of_openjdk_projects.md)
       * [OpenJDK 8 SonarQube passos](intermediate-steps/openjdk8_sonarqube_steps.md)
       * [OpenJDK 9 SonarQube passos](intermediate-steps/openjdk9_sonarqube_steps.md)
       * [OpenJDK SonarQube Dashboard passos](intermediate-steps/openjdk_sonarqube_dashboard_steps.md)
   * [OpenJDK9 - jimage](intermediate-steps/openjdk9-jimage.md)
* [Passos Avançados](advanced-steps/advanced_steps.md)
   * [Compilando jcov](advanced-steps/building_jcov.md)
   * [Compilando sigtest](advanced-steps/building_sigtest.md)
   * [OpenJDK cobertura de código](advanced-steps/openjdk_code_coverage.md)
   * [Deep-dive Hotspot e ciaOpenJDK9](advanced-steps/deep-dive_hotspot_stuff.md)
   * [Compilador e cia](advanced-steps/compiler_stuff.md)
   * [Efetue mudancas no java.c & e rode com o Hotspot dentro do Eclipse](advanced-steps/change_javac_&_run_hotspot_from_within_eclipse.md)
   * [Efetue mudancas no java.c & e rode com o Hotspot dentro do CLI](advanced-steps/change_javac_&_run_hotspot_from_the_cli.md)
   * [Hackeando o JDK, compilando, efetuando o build & rodando testes especificos](advanced-steps/hacking_the_jdk,_compiling,_building_&_running_specific_tests_change_sources_in_the_jdk.md)
       * [Testando o Java antes do lançamento oficial](advanced-steps/testing_java_early_project.md)
       * [Efetuando mudancas na classe Random.java class](advanced-steps/change_the_randomjava_class_to_amend_the_below_method.md)
       * [Efetuando mudancas na classe StringBuffer.java](advanced-steps/change_the_stringbufferjava_class_to_add_the_below_method.md)
       * [Como usar o JTReg… - Java Regression Test Harness](advanced-steps/how_to_use_jtreg_-_java_regression_test_harness.md)
           * [Preparações](preparations.md)
           * [Problemas](advanced-steps/problems.txt.md)
           * [Exemplos de anotações no header de arquivos de teste](advanced-steps/test-annotations.md)
* [Problemas conhecidos](known-issues/known_issues.md)
   * [Linux/Unix](known-issues/known_issues_linuxunix.md)
   * [MacOS](known-issues/known_issues_macos.md)
   * [Windows](known-issues/known_issues_windows.md)
   * [Virtual Machine](known-issues/known_issues_virtual_machine.md)
   * [Mercurial](known-issues/known_issues_mercurial.md)
   * [SonarQube](known-issues/known_issues_sonarqube.md)
* [Canivete suiço de scripts para desenvolvedores do OpenJDK](handy-scripts-for-OpenJDK-developers.md)
* [Agradecimento e suporte](thanks_and_support.md)
* [Feedback](feedback.md)
* [Contribuidores deste livro](contributors.md)
* [Como contribuir a este livro](contribute.md)
