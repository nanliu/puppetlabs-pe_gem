# puppet-pe_gem module

This module provides management of Ruby gems for Puppet Enterprise.

    package { 'json':
      ensure => present,
      provider => pe_gem,
    }
