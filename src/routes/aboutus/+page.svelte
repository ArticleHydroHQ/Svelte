<script>
    import aboutUsBlocks from 'card.svelte';
  
  const aboutUsBlocks = [
    {
      name: 'John Doe',
      functionText: 'Founder and CEO',
      introduction: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
    },
    {
      name: 'Jane Smith',
      functionText: 'Marketing Director',
      introduction: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.'
    }
  ];
</script>

<aboutUsBlocks {aboutUsBlocks} />

  